### python決策與選擇結構(SELECTION /DECISION) 

- 程式語言都會有的決策與選擇結構(SELECTION /DECISION):C C++ C# 

```
[1]if(判斷條件) : 是非題｜對的才要做
[2]if(判斷條件) ...elsif(判斷條件)
[3]if(判斷條件) ...else : 二選一
[4]if(判斷條件)...elsif(判斷條件) ...else: 多選一
[5]各種判斷條件==> 善用 AND   OR
```

- Python沒有switch(Python 3.10之前)
- python switch實作
  - 在 Python 3.10 中使用 match 和 case 關鍵字實現 Switch 語句[Python Switch Statement – Switch Case Example](https://www.freecodecamp.org/chinese/news/python-switch-statement-switch-case-example/)
  - [4 Ways to implement Python Switch Case Statement](https://flexiple.com/python/python-switch-case/)

# [1]if ==>底下程式輸出為何?
- 資料來源 : https://www.w3schools.com/python/python_conditions.asp
```
a = 33
b = 200

if b > a:
  print("b is greater than a")
```
```
a = 33
b = 20

if b > a:
  print("b is greater than a")
```
# [2]if ...elsif ==>底下程式輸出為何?

## 範例1
```
a = 32
b = 33

if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```
## 範例2
```
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```
## 範例3
```
a = 35
b = 33

if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```

# 雙向判斷式（if⋯else）: 二選一｜一定要選的

```
a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
```
# [4]if ...elsif ...else  多選一｜一定要選的
```
a = 200
b = 33

if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```
# [5]各種判斷條件 ==> 善用  AND  OR
```
判斷是否為閏年
```
```
year= eval(input("請輸入年"))

if ((year%400==0) or (year%4==0 and year%100!=0)):
  print("{0} 是閏年".format(year))
else:
  print("{0} 不是閏年".format(year))
```



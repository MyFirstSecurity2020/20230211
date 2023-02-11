# SecurityFoscusOnline2023 上課資訊

# 上課所使用的平台
- [立馬點選加入線上上課平台(Google Meet)上課去](https://meet.google.com/anw-awov-hsw)
  - 8:50開放,9:20關閉連結(遲到太久 ==>就不要參加| 以後會更嚴格: 遲到==>就不要參加)
  - 參與的觀摩教師可自行安排登入時間,也請聯繫小編
- [CTF平台解題(平常沒開放~只有上課期間才會開放)](https://120.114.62.209/)
  - CTF平台會記錄解題的時間,請在上課及開放期間解完你會解的題目
  - 需要做學習歷程的同學,請及早多做準備(先將解題過程使用Windows的剪取工具解貼到你的powerpoint==>後續再加上你的心得)
  - 學習歷程報告盡量強調解題原理,不要只有答案及畫面
  - 平台原則上在上課後當天就會關閉 ==> 你要在兩天內完成會解的題目 ==>請配合時間|不要要求延長賽
  - 燃燒你的資安戰鬥力吧 ! 想想看 CTF戰隊選手兩三天內就要打完戰 你還有時間摸辜錒
  - 專注!專注!再專注!專注的學習 才是 王道!
  - 極限學習的模式:在極短時間內掌握學習主題的深刻內涵 
    - 三天內或三小時把C或C++學會?基本的~ 多深刻? 語法理解 ? 還是 ..就看你的 樓!
- [Discord課程討論區：https://discord.gg/yWCfDtQjzJ 同學互相討論區](https://discord.gg/yWCfDtQjzJ)
  - 嚴格禁止上傳答案(違背者取消證書|且不得參與後續研習活動)
- 上課簽到簿:請每日上課不要遲到
  - [2/11 簽到簿](https://forms.gle/wvuy8prixdNtkY2z9)
  - [2/12 簽到簿](https://forms.gle/zhP9Q5EYPzzRxvB88)
- [問卷調查](https://forms.gle/YUYmUJ16YFjvC8te6)
  - (最後填寫!一定要填寫,不然沒有證書) 
  - 問卷調查須正確填寫CTF註冊的使用者ID 以供驗證解題數作為通過課程考核的依據

# 開場白與上課模式[[0211課程的錄影]](https://youtu.be/YvQH03hj8mI)
- 務必先聽完如何使用本課程與相關規範
- 本課程採兩種模式進行:(1)預錄模式 (2)Google Meet線上直播模式
- 此次課程主要採 (2)Google Meet線上直播模式,部分解題採預錄模式(就是錄影後,放在YOUTUBE讓你觀看學習的啦)


# 第一天上課時程
## 早上 A1_MyFirstSecurity資安入門的第一堂課
- CTF 入門:透過參與CTF搶旗大賽學習資安實務 [線上課程]
  - CTF搶旗大賽
  - 註冊與登入CTF
  - 起手式---文件隱寫術之word隱身術{隱寫術101::STEG1}
    - 另一種解法 請參閱 [如何在Word中快速顯示或隱藏所有隱藏的文本？](https://zh-tw.extendoffice.com/documents/word/906-word-show-hide-hidden-text.html) 
  - 【自行完成】{隱寫術101::STEG2_Secret in PDF}
- 網站安全初體驗 == > Web101
  - Web101::Web-1:source code(隱藏在註解裡的FLAG)[[YOUTUBE教學錄影]](https://youtu.be/2GWc9hsw794)
  - Web101::Web-2:Easy_Robots.txt(Robot.txt的奧秘1)[[YOUTUBE教學錄影]](https://youtu.be/Ifi9VHGBhsY)
  - 【自行完成】Web101::web-3:Robots.txt(Robot.txt的奧秘2)[無提供解答][完成編碼與解碼問題時再回來解此題]
  - Web101::web-4:Curl-1:URL redirection的破招 [[線上解答]](./A1_MyFirstSecurity資安入門的第一堂課/web-4解答.md) [[YOUTUBE教學錄影]](https://youtu.be/Lwyp3tv66KQ)
  - Web101::web-5:HTTP method (HTTP method的奧義)[[線上解答]](./A1_MyFirstSecurity資安入門的第一堂課/web-5解答.md)
- 編碼與解碼 == >  編碼101  [[YOUTUBE教學錄影]](https://youtu.be/fu2jgb4SN7U)
  - Ascii 編碼與解碼[線上課程] {編碼101:Ascii}
  - 【自行完成】{編碼101:Base64}
  - 【自行完成】{編碼101:Base32}
  - 【自行完成】{編碼101:Morse code}
  - 【自行完成】{編碼101:第一堂base64編碼}
  - 【自行完成】{編碼101:第一堂Unicode}
  - BASE64原理說明 [[中文Wiki的說明]](https://zh.wikipedia.org/wiki/Base64) [[YOUYUBE教學錄影]](https://youtu.be/lFUb0cmHo1c)
  - 【自行完成】Base32原理說明
- 古典密碼學之破密分析 == > Crypto101  
  - 善用線上工具進行破密分析
  - 凱薩密碼 與【暴力破解法】{Crypto101::CRY1}  [[YOUYUBE教學錄影]](https://youtu.be/GY34Ewh6EoQ)
  - 【自行完成】{Crypto101::CRY2_凱撒密碼part2}
  - 【自行完成】{Crypto101::CRY3_ROT 13} 
  - 密碼棒加解密 Scytale [英文WIKI說明](https://en.wikipedia.org/wiki/Scytale) [中文WIKI的說明](https://zh.m.wikipedia.org/zh-tw/%E5%AF%86%E7%A2%BC%E6%A3%92)
    - 題目:Crypto101::CRY4 SCYTCRYPTO 密碼棒破密}  [[YOUYUBE教學錄影]](https://youtu.be/8XbZSa-1GkE)
  - Vigenère cipher  
    - 基本觀念 [課程線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A1_MyFirstSecurity%E8%B3%87%E5%AE%89%E5%85%A5%E9%96%80%E7%9A%84%E7%AC%AC%E4%B8%80%E5%A0%82%E8%AA%B2/Vigen%C3%A8recipher.md) [[YOUYUBE教學錄影]]()
    - Crypto101::CRY5題目解答[[YOUYUBE教學錄影]](https://youtu.be/P2fCkFC2eRA)
  - 【頻率分析法】的破密技術{Crypto101::CRY6}
  - 【自行完成】{Crypto101::CRY7_Rail Fence Cipher}
  - 【自行完成】{Crypto101::CRY8_ROT47}
## 下午 A2_Linux資安技術入門
- 預先作業
  - 首先完成你的 [github](https://github.com/) 申請
  - 在你的電腦下載 [virtual box](https://www.virtualbox.org/wiki/Downloads) 並安裝完成 [Virtualbox安裝:YOUTUBE影片](https://youtu.be/FC0CX71aGnc)
  - 匯入你要用的linux  [YOUTUBE教學影片](https://youtu.be/GTpQR7fZcwE)
  - 資料下載點(請先下載這些龐大的系統)
    - Kali Linux [下載點](https://drive.google.com/file/d/1m620Z7KAOSUOLdFH92FYLE2NINb-vJsn/view?usp=sharing)
    - Python會用到的Ubuntu Linux 18.04 LTS(已安裝好pwntools)  [下載點](https://drive.google.com/file/d/1aP-qCFP6jKsGYXtKy9ahwZleQSENEi7C/view?usp=sharing)
- 學習LINUX
  - 使用Google Colab
  - 連線到LINUX CTF去學習
  - 使用線上工具 [Online Linux Terminal](https://www.tutorialspoint.com/linux_terminal_online.php)
  - 使用虛擬機匯入LINUX學習 
- 快速認識Linux作業系統 [線上教材](./Linux/1.基礎linux入門.MD) [[YOUTUBE教學錄影]](https://youtu.be/0T4o81Vghio)
- LINUX指令(commands) == >  Linux 101 + Linux 102
  - [如何透過Windows連線到CTF平台解題](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/%E5%A6%82%E4%BD%95%E9%80%8F%E9%81%8EWindows%E9%80%A3%E7%B7%9A%E5%88%B0CTF%E5%B9%B3%E5%8F%B0%E8%A7%A3%E9%A1%8C.md) [[YOUTUBE教學錄影]](https://youtu.be/cULwZeGliuA)
  - Linux指令入門[線上教材](https://github.com/MyFirstSecurity2020/20230211/blob/main/Linux/2_0_.Linux%E5%9F%BA%E6%9C%AC%E6%8C%87%E4%BB%A4.MD)
  - [LINUX CTF 101解答 ](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2_1_Linux101%E8%A7%A3%E7%AD%94.md)  [[Linux1_教學錄影]](https://youtu.be/zLeU0XJAtws)
  - [LINUX CTF 102解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2_2_Linux%20102%E8%A7%A3%E7%AD%94.md) 
  - 課後你可以增加國外Linux的練習經驗喔 ~ 完成底下[linux練習](https://overthewire.org/wargames/bandit/) 不會解可以上網參看別人的解法
- 隱寫術(Steganography) == >  隱寫術101
  - 1_認識 隱寫術(Steganography)  [[線上教材]](./Linux/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/1_%E8%AA%8D%E8%AD%98%E9%9A%B1%E5%AF%AB%E8%A1%93%20Steganography.md) [[YOUTUBE教學影片]](https://youtu.be/EJk3l64WPsQ)
  - 2_圖片隱寫術之1:基本入門技_使用linux 基本指令file|strings|grep{隱寫術101::STEG3} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/2_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%9F%BA%E6%9C%AC%E5%85%A5%E9%96%80%E6%8A%80.md) [[YOUTUBE教學影片]](https://youtu.be/farL-eOUXZs)
  - 3_圖片隱寫術之2:圖片內嵌`含解答圖片`的解題 
    - 題目:隱寫術101::STEG4  [題目檔案](https://raw.githubusercontent.com/MyFirstSecurity2020/backup/main/steg/steg101/carter.jpg) [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/edit/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/3_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E4%B9%8B2_%E5%9C%96%E7%89%87%E5%85%A7%E5%B5%8C%E8%A7%A3%E7%AD%94%E5%9C%96%E7%89%87%E7%9A%84%E8%A7%A3%E9%A1%8C.md) [[YOUTUBE教學影片]](https://youtu.be/GLpg4rTmiqg)
  - 4_圖片隱寫術之3:圖片的metadata{隱寫術101::STEG5} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A2_Linux%E8%B3%87%E5%AE%89%E6%8A%80%E8%A1%93%E5%85%A5%E9%96%80/2.%E9%9A%B1%E5%AF%AB%E8%A1%93%E5%85%A5%E9%96%80/4_%E5%9C%96%E7%89%87%E9%9A%B1%E5%AF%AB%E8%A1%93%E4%B9%8B3_%E5%9C%96%E7%89%87%E7%9A%84metadata.md)
- Linux 鑑識分析入門 == >  Network101
  - 1.鑑識分析與Wireshark入門 [線上教材](./Linux/3_1_鑑識分析與Wireshark入門.md)
  - 2.網路鑑識分析第一步:使用file | strings | grep 指令進行分析[線上教材](./Linux/3_2_網路鑑識分析第一步_使用linux基本指令進行分析.md)
    - Network101::NET1
    - Network101::NET2
  - 3.wireshark封包分析 == >HTTP Basic Authentication(認證)封包{Network101::NET3} [線上教材](./Linux/3_3_使用wireshark分析HTTPBasicAuthentication.md) [[YOUTUBE教學影片]](https://youtu.be/IH3Q7jdDX5s)
  - 4.wireshark封包分析 == >檢視出user使用的瀏覽器版本號{Network101::NET4} [線上教材](./Linux/3_4_使用wireshark檢視出user使用的瀏覽器版本號.md) [[YOUYUBE錄影]](https://youtu.be/GnufKfXOSG4)

# 第二天上課時程 A3_Python程式與資安應用入門 
## 早上: Python 快速上手
- 1.開發環境與基本輸入與輸出 
  - python開發環境 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/0_python開發環境.md) [[YOUTUBE教學影片]](https://youtu.be/9Doo0hgbpow)
  - 基本輸入與輸出 格式化輸出 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/1_基本輸入與輸出.md)  
- 2.Python資料型態(data Type)及其各種運算 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/2_資料型態及其運算.md)  [[YOUTUBE教學影片]](https://youtu.be/zCfVPuJWRg8) 
- 3.python決策與選擇結構 [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/3_python決策與選擇結構.md) [YOUTUBE預錄影片]() 
- 4.廻圈(loop) [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/4_廻圈loop.md) [[YOUTUBE教學影片]](https://youtu.be/12I7eNHQpgY) 
- 5.函數(function) [線上教材](./A3_Python程式與資安應用入門/A_Python程式入門/5_函數.md) [[YOUTUBE教學影片]](https://youtu.be/tRtsxZ73LVk) 

## 下午: Python 資安應用
- 1.使用Python求解編碼與解碼問題
  - 👍使用Python程式與內建函數進行ASCII的編碼與解碼 [[YOUTUBE教學影片]](https://youtu.be/0Tr-X0Lpi7g)
  - 👍使用Python標準函式庫進行BASE64的編碼與解碼 [[YOUTUBE教學影片]](https://youtu.be/z2jxjkl5X-4) 
  - 編碼102_Internetwache CTF 2016_The hidden message [解答]()
  - 編碼102:SECCON CTF 2014: Easy Cipher [解答]()
- 2.使用Python求解古典密碼破密分析問題 Crypto102
  - 【自行完成】{Crypto102::CRY11_PythonCrypto} [解答]()
  - 使用Python求解變形caesar密碼{Crypto102::CRY12_變形caesar密碼} [解答]()
  - 使用Python求解affine-cipher{Crypto102::CRY13_affine-cipher} [解答](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/3_Python%E5%8F%A4%E5%85%B8%E7%A0%B4%E5%AF%86%E6%B3%95/2_%E4%BD%BF%E7%94%A8Python%E6%B1%82%E8%A7%A3affine-cipher.md)
- 3.使用Python求解PPC(Professional Program Code)問題
  - 👍PPC(Professional Program Code)之使用 nc 遠端連線{PPC101::PPC1_hello world} [線上教材](https://github.com/MyFirstSecurity2020/SecurityFoscusOnline2023/blob/main/A3_Python%E7%A8%8B%E5%BC%8F%E8%88%87%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/B_Python%E8%B3%87%E5%AE%89%E6%87%89%E7%94%A8%E5%85%A5%E9%96%80/4_Python%20%20PPC%E5%AF%A6%E6%88%B0%E6%8A%80/PPC(Professional%20Program%20Code)%E4%B9%8B%E4%BD%BF%E7%94%A8%20nc%20%E9%81%A0%E7%AB%AF%E9%80%A3%E7%B7%9A%7BPPC101::PPC1_hello%20world%7D.md)  [[教學影片]](https://youtu.be/zJF4LBBHHrE)
  - 👍PPC(Professional Program Code)之pwntools快速入門與示範解題{PPC101::PPC2_3rd} [線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技//PPC(Professional%20Program%20Code)%E4%B9%8Bpwntools%E5%BF%AB%E9%80%9F%E5%85%A5%E9%96%80%E8%88%87%E7%A4%BA%E7%AF%84%E8%A7%A3%E9%A1%8C.md) [[教學影片]](https://youtu.be/XVRYjrbBYw4)
  - PPC101::PPC3_beautify解答 [線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技//PPC101::PPC3_beautify%E8%A7%A3%E7%AD%94.md)
  - 【自行完成】自行完成 PPC101::PPC4_count[線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技//PPC101::PPC4_count%E8%A7%A3%E7%AD%94.md)
  - PPC101::PPC5_lambda解答 [線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技/PPC101::PPC5_lambda%E7%AD%94%E6%A1%88.md)
  - PPC101::PPC6_money解答 [線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技/PPC101::PPC6_money%E7%AD%94%E6%A1%88.md)
  - PPC101::PPC7_calendar解答 [線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技/PPC101::PPC7_calendar%E8%A7%A3%E7%AD%94.md)
  - 👍PPC101::PPC8_temperature答案 [線上教材](./Python/B_Python資安應用入門/4_Python PPC實戰技/PPC101::PPC8_temperature%E7%AD%94%E6%A1%88.md)  [[教學影片]](https://youtu.be/_YGpD7wXGOo)





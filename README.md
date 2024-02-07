# 第六大陸 ![image](https://github.com/Yueem/T6/assets/116643627/5f52a757-f56a-4552-8902-50848b0d5920)  
:bell:左右軟體開發的社群養成遊戲《第6大陸》又稱This6(玩家簡稱T6)，是由廣州左右軟體技術有限公司開發並經營的網頁遊戲。它是一款專為學生、上班族設計的FLASH虛擬互動社區，強調由自己去創造並享受生活。  
:exclamation:因遊戲開發較早，使用了已被移除的flash插件。導致海外玩家都無法下載與更新flash版本。  
:file_folder:本儲存庫提供**flash插件**，與推薦的**遊戲環境**，以及在遊玩過程中可能造成的**遊戲卡頓**問題。  
# :mag:瀏覽器  
使用瀏覽器為360極速瀏覽器-13.0.2290.0  
[下載鏈接](https://down.360safe.com/cse/360cse_13.0.2290.0.exe)  
![image](https://github.com/Yueem/-/assets/116643627/4b94be47-a7af-40d1-8d1f-742aee350a0c)  
![image](https://github.com/Yueem/-/assets/116643627/85a55fc2-7e5e-40f1-ae40-2bdb5c502e71)  
安裝完成在`360Chrome\Chrome\Application\components`下添加 :open_file_folder: ppflash  
![image](https://github.com/Yueem/T6/assets/116643627/addc1476-806a-47c8-a788-d4f19c14e76c)  
重開瀏覽器即可進入了哦~  


  
# :bangbang:瀏覽器推薦(可做可不做)  
將瀏覽器右上角![image](https://github.com/Yueem/T6/assets/116643627/2c6782d4-8854-42a0-bcbd-caa5627119ad)
`选项>基本设置`將打开页面更換成```http://zhaijidi.com/```  
(官方公告此網址維護中有些用戶無法打開，若無法打開，將網址更換為```http://a1.zhaijidi.com/```)  
![image](https://github.com/Yueem/T6/assets/116643627/51b8ab94-2400-4e6d-9671-0f8a64a1a665)  
並將默認瀏覽器關閉  
![image](https://github.com/Yueem/T6/assets/116643627/3b1ab840-7310-470a-a425-4a3814ea36e6)  
在`界面設置`中取消勾選，如下圖  
![image](https://github.com/Yueem/T6/assets/116643627/e6a6a1b5-42d2-4b68-a9d4-ae000b940219)  
# Flash插件  
:open_file_folder:ppflash內含:electric_plug:`pepflashplayer32_29_0_0_171.dll`  
# 更改遊戲IP  
如果遊戲運行不順暢可以更改連線IP來改善遊戲卡頓的問題  
方法如下  
官方共提供3種不同的連線的IP  
電信
```
121.9.243.212 fms.a1.this6.com
121.9.243.212 a1.this6.com
121.9.243.212 a.this6.com
121.9.243.212 a.center.this6.com
121.9.243.212 s.a1.this6.com
121.9.243.212www.this6.com
121.9.243.216 zhaijidi.com
121.9.243.216 www.zhaijidi.com
121.9.243.21 m.this6.com
121.9.243.216 a1.zhaijidi.com
```
聯通  
```
163.177.178.196 fms.a1.this6.com
163.177.178.196 a1.this6.com
163.177178.196 a.this6.com
163.177.178.196 a.center.this6.com
163.177.178.196 s.a1.this6.com
163.177.178.196 www.this6.com
163.177.178.200 zhaijidi.com
163.177.178.200 www.zhaijidi.com
163.177.178.200 m.this6.com
163.177.178.200 a1.zhaijidi.com
```
移動  
```
183.232.9.206 fms.a1.this6.com
183.232.9.206 a1this6.com
183.232.9.206 a.this6.com
183.232.9.206 a.center.this6.com
183.232.9.206 s.a1.this6.com
183.232.9.206 www.this6.com
183.232.9.205zhaijidi.com
183.232.9.205 www.zhaijidi.com
183.232.9.205 m.this6.com
183.232.9.205 a1.zhaijidi.com
```   
可在`cmd`中ping看看3種IP，選一組連線時間最短。
```
ping -n 5 121.9.243.212
ping -n 5 163.177.178.196  
ping -n 5 183.232.9.206  
```  
`以系統管理員身份執行`打開cmd，`WIN+R`打`cmd`，按`Ctrl +Shift+ENTER`  
切換路徑並打開hosts  
```
cd C:\Windows\System32\drivers\etc
notepad hosts  
```
選一組IP貼上並保存  
![image](https://github.com/Yueem/T6/assets/116643627/3563c7ce-61ee-4c93-86fc-8c790ee96460)  

刷新  
```
ipconfig /flushdns  
```  

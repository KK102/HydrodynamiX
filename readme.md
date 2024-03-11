# HydrodynamicX v1.12.1! 
> aka.HDNX, HydrodynamicXperiments, 流體力學.實驗版
> 
> @nKai.Lab / feat.JT.0
> 
> Discord: @nkkai.k

## 官方版機器人邀請連結：
https://shorturl.at/ilvTX

## 自行建置使用方式 (1.12.1以及往後的版本)：
- 事先準備
  - 去discord developers裡面建立機器人
  - 下載最新釋出的版本壓縮檔
  - **解壓縮到一個空的資料夾** (**非常重要，這個資料夾會用來儲存所有log及其他必要檔案**)
- 環境建構
  - 安裝 **Python 3.10**
    - 3.10以上未測試
  - 安裝適合自己的IDE
    - HDNX 1.12.1 更新後此步驟不必要，若要修改程式才安裝
  - 複製金鑰 (token) 貼在 **.env** 裡面，覆蓋 **bot token here**
    - 範例：`TOKEN = '12345678'`
  - 執行`start_bot.bat`
    - 首次執行module安裝完後會自動關閉，重新啟動即可正常運作
    - 也可手動安裝module(若無法啟動) https://github.com/nKiux/Discord-Bot-Setup
 
> 若需要1.12.1之前的版本可以查看壓縮檔內的`readme.txt`，最後一行修改為：`pip install requests`

- 常見問題：

  - 若開啟`start_bot.bat`後一直閃退，則請您檢查：
    - `.env`文件有沒有配置正確，請再檢查一次金鑰是否正確

# 提供的功能：
- **早安能量！**
  - 使用指令初始化後，在任意頻道輸入： `早安` / `早上好` 即可獲得早安能量，在能量到達25後，會傳送訊息通知！
  - 讓您組隊起床！
- **訊息紀錄：**
  - 紀錄伺服器內最近的幾條訊息
  - 支援**已被刪除的訊息**

- **圖片API：**
  - 隨機傳送動漫圖片
  - **自動偵測頻道是否為*NSFW***

- **遊戲：**
  - 俄羅斯轉盤 Russian Roulette
  - 擲骰子 Roll A Dice

- **隨機本子：**
  - 從n站隨機抽取本子

- **情緒控管模組：**
  - 自動偵測冒犯語句，並提供協助

- **NNN倒數：**
  - 11月限定功能，懂的都懂

- **個人備忘錄：**
  - 紀錄、閱讀、清除個人的備忘錄

- **POG!**
  - 用看看就知道了

- **獲取伺服器ID：**
  - 顯示您伺服器的ID和您個人的ID



> @nKai.Lab / feat.JT.0

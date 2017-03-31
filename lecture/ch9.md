# 9. 處理動態網頁 (Selenium Webdriver)

* 範例: `ch9/bot_house.py`
* 與其模仿瀏覽器，不如直接使用瀏覽器
    * 優點: 能夠解決大部分的障礙
    * 缺點: 執行速度, 例外處理...
* 前置作業
    * 安裝 selenium library (已經包含在 requirements.txt 中)
    * 下載 [Chrome Webdriver 執行檔](https://sites.google.com/a/chromium.org/chromedriver/downloads), 解壓縮後放在專案目錄下
* Webdriver 可以做的事:
    * 定位網頁元件
    * 點擊, 輸入文字, 選擇選單, 拖拉...
    * 下載目前看到的網頁原始碼 (後續使用 Beautifulsoup 解析並取得資訊)
* 範例: http://www.bot.com.tw/house/default.aspx
* 補充資料: Webdriver 的執行檔也可以使用 [PhantomJS](http://phantomjs.org/download.html), 可以在背景模仿瀏覽器行為, 或可加快程式執行速度
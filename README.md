<!-- TOC depthfrom:1 depthto:1 orderedlist:false -->

- [Android-MVVM-Taipei-Travel](#android-mvvm-taipei-travel)
- [Flutter-course_system](#flutter-course_system)
- [Blockhain-NFT-Wallet-AndroidKotlin-iOsSwift-nodejs](#blockhain-nft-wallet-androidkotlin-iosswift-nodejs)
- [Vue-D3-python](#vue-d3-python)
- [Android-TsNode](#android-tsnode)
- [Android-MapRunner](#android-maprunner)
- [Angular-C#-Finzview](#angular-c-finzview)
- [Angular-Ionic-Firebase-LangStar](#angular-ionic-firebase-langstar)
- [VSCode Extensions - WOVO](#vscode-extensions---wovo)
- [Chrome Extensions - StockInfoSearch](#chrome-extensions---stockinfosearch)
- [JavaSE-Aechart2016](#javase-aechart2016)
- [Android-Google Associate Android DeveloperAAD](#android-google-associate-android-developeraad)

<!-- /TOC -->















# `Android-MVVM-Taipei-Travel`

以MVVM架構一以台北旅遊為基礎之應用
- dagger:hilt (DI)
- retrofit (RESTful API Client)
- glide (Image loading/caching)
- coroutines

feature
- node mode
- landscape layout
- hero image
- map interactive

[Github](https://github.com/jimliuxyz/android-mvvm-taipei-travel)

### portrait
<img src="images/TaipeiTravel/screen_record_portrait.gif" alt="image" width="300" height="auto">


### landscape
<img src="images/TaipeiTravel/screen_record_landscape.gif" alt="image" width="auto" height="350">

<!-- Flutter-course_system -->
# `Flutter-course_system`
架構一選課系統 包含單元與整合測試 

[Github](https://github.com/jimliuxyz/course_system)


# `Blockhain-NFT-Wallet-Android(Kotlin)-iOs(Swift)-nodejs`

專案簡述：以`乙太坊智能合約`搭建電子錢包應用 包含心化會員系統 與手機前端應用。

程式語言：Javascript(nodejs/truffle/web3js/socket.io), Kotlin(Android), Swift(ios), solidity(區塊鏈智能合約)

資 料 庫：Mongodb, ganache(模擬區塊鏈結點)

其他工程：AWS(EC2)

Github
- [Backend](https://github.com/jimliuxyz/coinpocket)
- [Android](https://github.com/jimliuxyz/coinpocket-android)
- [iOs](https://github.com/jimliuxyz/coinpocket-ios)

### Architecture
<img src="images/Blockchain/architecture.png" alt="image" width="300" height="auto">

### Android
<img src="images/Blockchain/android-login-jim.png" alt="image" width="200" height="auto">
<img src="images/Blockchain/android-transfer-merry.png" alt="image" width="200" height="auto">

### iOS
<img src="images/Blockchain/ios-transfer.png" alt="image" width="200" height="auto">

<!-- Vue-D3-python -->
# `Vue-D3-python`
專案簡述：以台中市2023年7月交通事故為資料,進行數據處理 並展示事故尖峰時刻、各區事故量競賽、事故分佈地圖、各區事故量(雲)、事故類型(雲)。

程式語言：Javascript(vue3, d3js), python(flask/pandas)

其他工程：docker

[應用連結](https://tx.finzview.com/)

[Github](https://github.com/jimliuxyz/trafficanalysis)

<img src="images/TaichungTraffic/screenshot1.png" alt="image" width="300" height="auto">

<img src="images/TaichungTraffic/screenshot2.png" alt="image" width="300" height="auto">


# `Android-TsNode`
專案簡述：翻譯筆記上選取內容並儲存 上線play store。

程式語言：Kotlin

其他工程：google translate api

<img src="images/TsNote/home.jpg" alt="image" width="250" height="auto">
<img src="images/TsNote/content.jpg" alt="image" width="250" height="auto">

<img src="images/TsNote/translate.jpg" alt="image" width="250" height="auto">
<img src="images/TsNote/setting.jpg" alt="image" width="250" height="auto">

# `Android-MapRunner`
專案簡述：以兩隻手機 模擬跑步機與行動裝置間的互動情境。

- Kotlin / Room / Retrofit
- 畫面翻轉狀態保留
- 儀表板以Sketch繪製與切版
- 自定義View(儀表板) 加減速指針動畫

### 模擬`跑步機`
- 等待藍芽裝置連入
- 連入後 開始定位 並透過google api下載行進路線 (終點預設為’台中火車站’)
- 開始位置移動的模擬 並傳送給手持裝置

<img src="images/MapRunner/treadmill-portrait.jpg" alt="image" width="250" height="auto">
<img src="images/MapRunner/treadmill-landscape.jpg" alt="image" width="auto" height="250">

### 模擬`手持裝置`
- 搜尋與連接藍芽裝置
- 連接後 開始接收移動位置 顯示於地圖 並寫入資料庫

<img src="images/MapRunner/handset-scan.jpg" alt="image" width="250" height="auto">
<img src="images/MapRunner/handset-running.jpg" alt="image" width="250" height="auto">
<img src="images/MapRunner/handset-records.jpg" alt="image" width="250" height="auto">


<!-- Angular-C#-Finzview -->
# `Angular-C#-Finzview`
[Finzview連結](https://finzview.com/)

專案簡述：滑動式瀏覽金融產品 過濾器 展示K線圖與技術分析 財報 新聞 快速連結 社群登入 多語系。

程式語言：TypeScript(Angular/open api/lightweight charts(tradingview)/chartjs), Kotlin(Android), SCSS, C#(.net core/swagger)

資 料 庫：MySql、Influxdb(時序)

其他工程：docker,rabbitmq,redis,nginx,haproxy,cdn,paypal,ecpay,google oauth/google one tap signin

<img src="images/Finzview/finzview_chart.gif" alt="image" width="300" height="auto">

<img src="images/Finzview/finzview_settings.gif" alt="image" width="300" height="auto">


# `Angular-Ionic-Firebase-LangStar`
語言單字學習 類似單字卡的分享平台
- 以Ionic(Angular)開發的Hybrid App
- 後台用Firebase 包含social login
- 以標籤機制區分各國語言與內容
- 過往操作可離線使用(PWA)


<img src="images/LangStar/01.png" alt="image" width="250" height="auto">
<img src="images/LangStar/02.png" alt="image" width="250" height="auto">

<!-- VSCode Extensions -->
# `VSCode Extensions - WOVO`
專案簡述：VSCode延伸模組 輸入發音導讀工具。

程式語言：Javascript
[Github](https://github.com/jimliuxyz/wovo)

[marketplace](https://marketplace.visualstudio.com/items?itemName=jimliuxyz.wovo)


<!-- Chrome Extensions -->
# `Chrome Extensions - StockInfoSearch`
專案簡述：Chrome延伸模組 股票相關網站搜尋。可以分類/拖拉/編輯/自訂

程式語言：Javascript

[marketplace](https://chromewebstore.google.com/detail/stock-info-search/ljjploppkgcnnlkmfbblimlaegicbpdf?hl=zh-TW)


<img src="images/StockInfoSearch/sis-settings.jpeg" alt="image" width="500" height="auto">

<img src="images/StockInfoSearch/sis-ui.png" alt="image" width="500" height="auto">


# `JavaSE-Aechart(2016)`
金融工具
- 接收DDE或券商提供之API做`即時報`價與`委託交易`
- 能夠`動態編譯`腳本程式 用以`繪圖`或`分析選股`或執行`程式交易`
- 可動態匯入第三方jar或ocx

<img src="images/Acechart/main.png" alt="image" width="500" height="auto">

# Android-Google Associate Android Developer(AAD)
<img src="images/Others/google-AAD.png" alt="image" width="500" height="auto">

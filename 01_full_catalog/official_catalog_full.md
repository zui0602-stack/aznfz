# 官方文檔完整索引
來源：官方文檔入口與左側目錄。

## 01. 00_入門與必看
1. 準備工作&下載
2. 使用流程
3. 最佳腳本實踐(必看)
4. 開發環境(IDE)
5. 0基礎1天學會JS
6. AI自動生成腳本

## 02. 01_FAQ常見問題
1. 常見問題
2. 冰狐的腳本安全嗎？是否會泄漏？
3. 相對autojs的優勢
4. 冰狐必須開啟無障礙嗎？
5. 可以脫離冰狐後端(不聯網)執行腳本嗎？
6. 如何執行手機裡的離線腳本？
7. 支持卡密(註冊碼)功能嗎？
8. 支持模擬器和雲手機嗎？
9. 支持藍牙(USB)HID硬件嗎？
10. 支持定制ROM嗎？
11. 不編程如何實現自動化腳本？
12. 如何實現團隊協作開發？
13. 如何定制自己的app？
14. 什麼是調試模式和發布模式？
15. 如何開啟調試功能？
16. 如何發布腳本？
17. 如何調試腳本程序和智能搭建？
18. 子賬戶如何登錄？
19. tag詳解
20. 獲取當前app的包名和窗口名
21. 查看控件各種屬性
22. 通過tag搜索不到控件怎麼辦？
23. 目標控件沒有text也沒有id如何處理？
24. 操作控件view時出現錯誤或者異常怎麼辦？
25. 粘貼文本失敗如何處理？
26. 點擊控件無效如何處理？
27. 滾動頁面失敗如何處理？
28. 沒有編程經驗可以使用智能搭建嗎？
29. 運行結果和預期不一樣怎麼辦？
30. 模塊family參數表示什麼意思？
31. 出現服務異常提示
32. 設備在離線和在線間切換或者經常離線
33. 如何傳遞外部參數給腳本？
34. 通過findView有時能找到有時找不到？
35. 如何設置默認腳本？
36. 開發者如何快速高效接單？

## 03. 02_JS及平台特性
1. js
2. 例子
3. 數據類型及常量
4. 運算符
5. 語句
6. 腳本特性
7. 系統事件和回調
8. 系統內置常量

## 04. 03_JS函數庫_數組集合字符串正則數學日期JSON控制台
1. 數組
2. concat連接多個數組
3. contains數組是否包含值
4. join合併數組為字符串
5. push數組末尾添加
6. pop數組末尾刪除
7. reverse顛倒元素順序
8. shift刪除第一個元素
9. slice獲取子數組
10. sort排序
11. splice添加或者刪除元素
12. unshift向數組頭添加
13. find查找數組
14. shuffle洗牌
15. randomPick隨機挑選n個值
16. sum求和
17. range生成數組
18. 集合Set
19. Set構造函數
20. Set添加元素
21. Set添加其他容器
22. Set刪除元素
23. Set轉數組
24. 字符串
25. String構造函數
26. charAt獲取字符
27. charCodeAt獲取unicode字符
28. concat連接字符串
29. indexOf查找字符串
30. lastIndexOf從末尾查找
31. remove刪除字符串
32. match匹配字符串
33. replace替換字符串
34. slice提取部分
35. split分割
36. substring提取字符串
37. substringBefore
38. substringAfter
39. substringBeforeLast
40. substringAfterLast
41. includes是否包含字符串
42. startsWith是否以某字符串開始
43. endsWith是否以某字符串結尾
44. trim去除兩邊空格
45. trimAll去除所有空白字符
46. extractInteger提取Integer
47. extractNumber提取number
48. getBytes獲取字節數組
49. toUpperCase轉大寫
50. toLowerCase轉小寫
51. 正則表達式
52. RegExp構造函數
53. exec執行
54. test測試
55. Math數學函數
56. sin
57. asin
58. cos
59. acos
60. tan
61. atan
62. atan2
63. exp
64. log
65. pow
66. sqrt
67. abs
68. ceil
69. floor
70. round
71. max
72. min
73. random
74. Date日期構造
75. 日期轉字符串
76. 獲取/設置日月年時分秒毫秒
77. JSON
78. JSON.parse
79. JSON.stringify
80. console
81. console.log
82. console.error
83. console.warning
84. console.info

## 05. 04_全局函數
1. 調用腳本
2. UI中執行任務
3. 停止/暫停/繼續執行腳本
4. 退出登錄
5. 啟動app
6. 停止app
7. 獲取設備/用戶/全局自定義數據
8. 自動獲取最佳自定義數據
9. 設置自定義數據
10. 延時
11. 發送消息
12. 獲取當前/最新冰狐版本
13. 獲取app名稱
14. 獲取前台app名/包名
15. 是否開啟無障礙
16. 打開無障礙設置
17. 概率
18. 警告框
19. randInt/randFloat/randString
20. floatDim2int/parseInt/parseFloat/parseBoolean
21. strIsEmpty/strIsNotEmpty
22. 設置/獲取剪切板
23. Toast
24. 啟動頁面
25. shell
26. 獲取當前線程id
27. 開關wifi
28. 開關懸浮球
29. 重啟自動運行
30. 音量鍵啟停腳本
31. 獲取IP
32. 殺掉後台app
33. 安裝/卸載app
34. 打開應用信息頁
35. 瀏覽器打開url
36. 震動手機
37. 設置默認腳本
38. setOrientation
39. 設置/獲取Log級別
40. 設置離線log
41. 更新相冊
42. 生成/解碼二維碼
43. 條形碼編碼/解碼

## 06. 05_無障礙控件操作
1. 控件操作
2. 控件對象及屬性
3. 控件基本操作
4. 查找控件
5. 查找根控件
6. 點擊控件
7. 模擬手勢點擊
8. 模擬多點手勢點擊
9. 返回到某個頁面
10. 切換頁面
11. 切換多個頁面
12. 輸入文本/粘貼數據
13. 獲取控件顏色
14. 滾動
15. 手勢操作
16. 按下系統返回鍵
17. 最近任務頁
18. Home鍵
19. 長按電源鍵
20. 打開通知界面
21. 刷新界面
22. 通知事件回調
23. 窗口改變事件回調

## 07. 06_屏幕圖色OCR_Yolo
1. requestScreenShot申請截屏權限
2. screenShot截屏
3. 停止截屏
4. 獲取屏幕顏色
5. findColor找色
6. 多點找色
7. compareColors比較顏色
8. findImage找圖
9. 圖片是否相等
10. 圖片灰度化
11. 圖片二值化
12. 讀取圖片
13. 寫入圖片
14. bitmapClip裁切圖片
15. bitmap2bytes
16. bytes2bitmap
17. 請求鎖屏權限
18. 鎖屏
19. 亮屏
20. OCR
21. ocr文字識別
22. tessOcr文字識別
23. 服務端ocr
24. ocrFindView
25. ocrClick
26. ocrSwitchPage
27. ocrBack2Page
28. YoloV8
29. Yolo構造函數
30. Yolo init
31. Yolo detect
32. 模型訓練

## 08. 07_HID_ADB_Root_Shizuku_輸入法
1. 藍牙HID BLE
2. BLE connect/send/receive/click/swipe/home/back/recentApps/mouseMove/mouseUp
3. USB HID
4. USB connect/send/receive/click/swipe/home/back/recentApps/mouseMove/mouseUp
5. Shizuku
6. Shizuku init/requestPermission/connect/checkPermission/checkConnect/execCmd
7. ADB
8. ADB init/close/connect/click/swipe/home/back/recentApps/enter/key/execCmd
9. Root
10. isRooted/enableAccessibility/screenshot/click/swipe/home/back/recentApps/enter/key/execCmd
11. 輸入法
12. 輸入文本
13. 輸入命令
14. 獲取當前輸入法
15. 顯示輸入法選擇框

## 09. 08_智能搭建腳本
1. 智能搭建
2. 使用步驟
3. 業務邏輯入口
4. 啟動APP
5. 查找控件並處理
6. 搜索控件
7. 搜索根控件
8. 點擊
9. 通用點擊
10. 點擊進入頁面
11. 返回頁面
12. 滾動處理
13. 通用滾動
14. 按返回鍵
15. 循環處理
16. 跳出循環
17. 遍歷容器
18. 概率
19. 日誌
20. 彈出框
21. 延時
22. 刷新當前頁面
23. 最近運行app
24. 顯示桌面
25. 輸入法輸入文本
26. 粘貼文本
27. 獲取控件文本
28. 獲取自定義數據
29. 添加自定義數據項
30. 搜索控件並循環處理
31. 條件處理
32. 數據處理
33. 導入腳本
34. 調用腳本
35. 調用FaaS
36. 調用函數
37. 調度腳本
38. 調用自定義模塊
39. 自定義模塊
40. 退出執行
41. 定時
42. GET網絡請求
43. POST網絡請求
44. 模塊組
45. JS模塊
46. 音頻模塊
47. 手勢操作
48. 寫文件
49. 獲取控件顏色
50. 獲取屏幕顏色
51. 截圖
52. 找色
53. 比較顏色
54. 找圖
55. OCR文字識別
56. OCR點擊
57. OCR點擊進入頁面
58. OCR返回頁面
59. 藍牙初始化
60. 藍牙發送數據
61. USB初始化
62. USB發送數據
63. Yolo初始化
64. Yolo檢測圖片
65. 亮屏
66. 變量聲明
67. 彈窗處理
68. 廣告處理
69. 窗口變化處理
70. 通知處理

## 10. 09_UI用戶界面
1. UI介紹
2. 自定義登錄UI
3. 安裝UI界面
4. 獲取UI控件
5. 動態創建UI
6. 打開/關閉UI界面
7. 顯示對話框
8. 顯示彈出菜單
9. 顯示/關閉懸浮對話框
10. 配置懸浮按鈕
11. onUIResume/onUIPause/onBackPressed
12. 模板fullscreen/width/height
13. View id/width/height/padding/layoutMargin/backgroundColor/backgroundImage/visibility
14. View click/longClick
15. setBackgroundColor/setBackgroundImage/setVisibility/setPadding/setMargin/on/off/postDelay/cancelDelay
16. ViewGroup add/remove/removeAll
17. Text text/gravity/size/color/lines/maxLines/style/ellipsize/setSize/setColor/setGravity/setText/getText/value
18. Input hint/inputType
19. Button
20. Image src/scaleType/setSrc
21. WebView pageStarted/pageFinished/consoleMessage/setUrl/goBack/goForward/refresh/exeJS/browser exeScript/stop/toast/url
22. Checkbox checked/onChecked/value
23. Radio checked/checked事件/value
24. RadioGroup
25. Spinner entries/onSelected/設置選中項/獲取選中位置/設置數據/value
26. ListView addData/setData/update/getData/onItemClick/onItemLongClick
27. LinearLayout orientation/layoutGravity/layoutWeight
28. FrameLayout/layoutGravity
29. VerticalScroll/HorizontalScroll
30. Flexbox flexDirection/flexWrap/justifyContent/alignItems/alignContent/order/flexGrow/flexShrink/flexBasisPercent/wrapBefore

## 11. 10_定時設備通知顏色網絡線程文件資料庫
1. setTimeout/clearTimeout
2. setInterval/clearInterval
3. setCronTask/clearCronTask
4. 設備名稱/型號/可用天數/製造商/OS版本/音量
5. 懸浮日誌顯示/配置/開關/顯示隱藏/清空
6. Notification顯示/取消通知
7. Toast配置/顯示/取消
8. Color parse/rgb/argb/alpha/red/green/blue/similarity
9. 網絡GET/POST/下載文件/調用FaaS/調用web服務/encodeURI/decodeURI
10. Thread構造/啟動/停止/獲取id/等待結束
11. 線程鎖構造/加鎖/解鎖
12. WebSocket構造/on/send/close
13. File構造/是否文件/是否目錄/列目錄/路徑/存在/大小/修改時間/文件名/創建目錄/刪除/移動/讀字符串/讀字節/寫/追加
14. 本地數據庫構造/關閉/刪除/表存在/執行SQL/查詢/開始事務/結束事務
15. 遠程數據庫構造/連接/斷開/執行SQL/查詢
16. Excel create/open/addRow/append/removeRow/removeColumn/read/rows/columns/close
17. 音頻播放/停止
18. 錄音請求權限/開始/停止
19. 錄視頻開始/停止

## 12. 11_AI_TTS_插件_存儲_加密
1. 大語言模型介紹
2. LLM構造函數
3. 調用大語言模型
4. 百度千帆例子
5. DeepSeek例子
6. TTS語音合成play/stop
7. 插件
8. 插件開發規則
9. 加載插件
10. Plugin對象
11. 本地存儲構造/讀數據/讀取所有/寫數據/刪除數據
12. AES構造/生成密鑰/編碼/解碼
13. DES構造/生成密鑰/編碼/解碼
14. RSA構造/生成密鑰/編碼/解碼
15. 摘要算法
16. base64編碼/解碼
17. gzip編碼/解碼

## 13. 12_團隊打包SDK雲原生OpenAPI
1. 團隊協作
2. 定制APP/打包
3. 腳本例子
4. 移動端SDK
5. 初始化引擎
6. 自動登錄
7. 登錄/登出
8. onCreate/onResume/onPause/onDestroy
9. 設置狀態變量listener
10. 設置消息listener
11. 執行腳本
12. 切換模式/獲取當前模式
13. 獲取設備名/用戶名
14. JS調用Java
15. FaaS移動端接口/服務端接口/業務處理/通用服務/實戰Demo
16. BaaS服務端API/用戶/設備/腳本/數據庫/網絡請求/緩存/鎖/卡密/base64/URI/自定義數據
17. OpenAPI
18. 獲取token
19. 刷新token
20. 獲取設備列表/信息/狀態
21. 啟動設備
22. 執行設備端腳本
23. 停止設備
24. 設置設備自定義數據
25. 獲取用戶信息/自定義數據
26. 創建用戶
27. 獲取用戶列表
28. 設置用戶支持的腳本
29. 創建/獲取/轉移卡密
30. 調用FaaS
31. 執行後端腳本

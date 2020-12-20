# BlazorDynamicLoader
由 David老師的程式架構所發想的專案


## 需求
1. 開發階段可以獨立執行
2. 執行階段可以直接嵌入
3. 模組化開發
4. 自動部署
5. 動態載入

## 想法
1. 利用Blazor component 封裝的特性加入功能頁面
2. 利用DI的方式引用套件進入專案
3. 學習nodejs 使用package.json 中使用github自動抓取套件的功能來做到動態讀取要載入的套件
4. 利用監控載入套件conf清單的方式動態調整要載入的component


## 目標
1. 可測試性
2. 可延展性
3. 可維護性

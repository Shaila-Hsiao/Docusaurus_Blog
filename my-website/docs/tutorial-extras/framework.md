---
sidebar_position: 1
sidebar_label: 'framework'
tags:
  - framework
  - Javascript
---

# 框架 framework:
:::tip 定義
開發前端時 提供一些架構性服務:
- 讓開發者容易操作開發
- 寫出來的code也比較容易重複使用
:::
## 發展原因: 
隨著專案規模逐漸增大，**程式複雜度不斷上升** :point_right:直接操作 **DOM 的缺點**也就逐漸浮出檯面
-  難以維護: 
    -  透過 JavaScript 處理互動內容，勢必要將結構、樣式寫到 JavaScript 的部份中，也就因此造成架構耦合度提高，程式碼管理困難
-  效能低落: 
    -  每一次response都需要先銷毀之前的document object model(頁面)，需要重建，狀態需要先傳回給web，再傳給下一個頁面
## 主要功能: 
- **data & UI 分開**: 可動態載入資料至html
- **模組化UI**: 網站內重複出現的元素，稱為 Components 。這些元件包括自己需要的 **結構、樣式、邏輯**
## ex: 
- Vue
- Angular
- React
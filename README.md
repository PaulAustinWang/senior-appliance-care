# 樂齡家電守護

長輩友善的家電服務介面：大字顯示、服務需求、使用偏好、來訪紀錄、操作筆記、保固與資料備份。

## 發布

網站入口是 `index.html`，樣式、圖示與 JavaScript 均已內嵌。

GitHub 儲存庫的 **Settings → Pages → Source** 選擇 **Deploy from a branch**，分支設為 `main`、目錄設為 `/ (root)`。更新 `main` 上的網站後，GitHub Pages 會自動發布。

## 資料

此公開儲存庫只包含網站檔案及部署設定，不包含客戶資料、資料庫、管理密碼或私人設定。

目前網站使用裝置上的瀏覽器儲存服務紀錄，GitHub Pages 不執行 Node.js／SQLite 後端；跨裝置共享服務資料與真正的門市派工需另外接上後端服務。

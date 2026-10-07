# 經濟系營隊活動報名系統

- 活動日期：10/7
- 活動時間：晚上 7:00-9:00
- 功能：新增、修改、刪除報名資料，串接 Google Apps Script / Google 試算表，送出後顯示入場證明。

## GitHub Pages
將 `index.html` 放在 repository 根目錄，於 Settings > Pages 設定由 main branch / root 發布。

## Apps Script
`apps-script/Code.gs` 為對應後端參考程式。請確認工作表名稱與 `SHEET_NAME` 一致，重新部署時使用正式 Web App deployment。

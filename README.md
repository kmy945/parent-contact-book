# 親師聯絡簿 v9.0

## 版本重點
- 完整保留原本的登入封面 `cover-clean.jpg`
- 登入後改為海洋泡泡 Dashboard
- 國中科別預設與自訂科別
- 教師 Google 登入、訪客模式、家長帳密登入
- 班級與學生資料管理
- 學生日常表現與聯絡事項
- 防禦性評語檢查與安全通知模板
- 公告、家長留言、簽閱、CSV/JSON 匯出
- 手機、平板、電腦響應式介面
- PWA 離線快取

## 手機上傳方式
將壓縮檔解壓縮後，把所有檔案上傳到 GitHub 儲存庫根目錄並覆蓋同名檔案；GitHub Actions 或 Firebase Hosting 會依原有設定重新部署。

## 注意
第一次正式使用前，請在 Firebase Authentication 開啟 Google 登入，並部署 `firestore.rules`。家長帳號預設密碼為 `123456`，建立正式資料後請立即更改。

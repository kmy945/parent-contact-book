# 親師聯絡簿完整可部署版

已連接 Firebase 專案 `parent-contact-book`。

## 主要功能
- 教師 Google 登入
- Cloud Firestore 雲端同步
- 班級與學生管理
- 聯絡事項、出缺席、重要表現
- 家長閱覽與回覆
- Excel 匯入與匯出
- 訪客預覽模式
- PWA 安裝支援

## Firebase Hosting 部署
在 Cloud Shell 執行：

```bash
firebase deploy --only hosting,firestore:rules --project parent-contact-book
```

> 部署前請確認 Authentication 的授權網域包含 `parent-contact-book.web.app`。

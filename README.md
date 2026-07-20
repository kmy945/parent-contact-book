# 親師聯絡簿 V6：資料匯出與家長問答版

## 新增功能
- 單筆新增學生只需座號、姓名
- 自動產生家長帳號與 8 碼初始密碼
- 家長可提出建議或問題，老師可直接回覆
- 匯出學生單日資料
- 匯出學生指定日期區間完整資料
- 匯出整班指定日期區間資料
- 訪客可儲存在目前裝置，但不會同步至 Firestore

## 部署
```bash
cd ~/parent-contact-book
git pull
firebase deploy --only hosting,firestore:rules
```

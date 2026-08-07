# 親師聯絡簿 V12.1｜手機穩定部署版

## 這一版的部署方式
GitHub 仍可保存程式碼，但 Firebase Hosting 更新不再依賴 GitHub Actions。
改用 Google Colab，手機或平板即可完成部署，並保留原本網址：

`https://parent-contact-book.web.app/`

## 完整包內含
- 親師聯絡簿 V12.1 網站更新包
- Google Colab 手機部署工具
- 網站原始檔案
- 使用說明

## 第一次使用
1. 解壓縮完整包。
2. 將 `親師聯絡簿_V12.1_手機部署工具.ipynb` 上傳到 Google Drive。
3. 使用 Google Colab 開啟。
4. 依序按每個儲存格左側的播放鍵。
5. 工具要求網站 ZIP 時，選擇 `親師聯絡簿_V12.1_網站更新包.zip`。
6. 工具要求 JSON 時，選擇從 Firebase 下載的服務帳戶 JSON。
7. 顯示「部署完成」後開啟網站檢查。
8. 最後在 Colab 選擇「執行階段 → 中斷連線並刪除執行階段」。

## 安全提醒
- 服務帳戶 JSON 不可上傳到 GitHub。
- 不可把 JSON 傳給其他人。
- Colab 部署完成後務必刪除執行階段。
- 若金鑰曾公開，請立即撤銷並重新產生。

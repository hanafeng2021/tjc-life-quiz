# 信徒生活須知｜線上練習

這是一個純前端靜態題庫練習網站，依上傳 PDF《信徒生活須知》整理題庫。

## 本機預覽

```bash
python3 -m http.server 8000
# 開啟 http://localhost:8000
```

## 部署 GitHub Pages

1. 建立 GitHub Repository。
2. 上傳本資料夾所有檔案到根目錄。
3. 到 Settings -> Pages，選擇 branch 與 root。
4. 等待 GitHub Pages 發布。

## 題庫格式

題庫在 `questions.json`，每題包含：id、level、round、subject、chapter、topic、question、options、answer、explanation。

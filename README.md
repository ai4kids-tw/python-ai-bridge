# 從 Scratch 到 Python × AI 銜接課｜學生筆記本

AI4kids 國中線上課程的學生端程式環境。學生用瀏覽器打開網址即可寫 Python，不用安裝、不用登入。

- 引擎：JupyterLite（Pyodide 核心，Python 在瀏覽器內執行）
- 內容：`content/` 每週一個資料夾，放課堂練習與作業的「學生版」筆記本
- 部署：推到 `main` 後，GitHub Actions 自動建置並發布到 GitHub Pages

## 這個 repo 是公開的
- 只放學生版筆記本與教學用模擬資料
- **不放解答版、學生資料或任何金鑰**

## 開啟某一週的筆記本
`https://ai4kids-tw.github.io/<repo 名稱>/notebooks/index.html?path=第1週/W01_課堂練習.ipynb`

## 學生作業存在哪裡
作業只存在該台電腦的瀏覽器裡。下課前請學生用 File → Download 下載 .ipynb 繳交。

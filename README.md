# NPI-Q SUMMARY

沿用原有 12 個 NPI-Q 項目與英文報告格式，並優化表格、字體及點選體驗的 GitHub Pages 靜態版本。

## 本次修改

- 勾選框與圓點為 28 × 28 px；整個儲存格都可點選，每列高度至少 68 px。
- 英文欄名與項目名稱放大，分數 0–3、0–5 直接顯示於圓點下方。
- 已選項目、鍵盤焦點、游標停留與停用狀態各有不同視覺回饋。
- 重新整理表格邊界、留白、字體層級、總分列與 Summary Output。
- **Generate Summary** 產生目前內容的英文文字報告。
- **Copy Report** 一鍵產生並自動複製目前報告，完成後顯示 Copied。
- **Reset** 一鍵清除所有選項與報告、總分歸零，並恢復為原始未填寫狀態。
- **診斷書生成欄**自動帶入 Severity Total 與 Caregiver Distress Total；可補填心智測驗日期及 CDR 分數。
- **複製診斷書文字**一鍵複製目前診斷書內容，完成後顯示已複製。
- 手機版按鈕自動換行，表格可在框內左右滑動，不會撐破整個頁面。
- 單一 `index.html`，無外部套件、無建置步驟。

## 上傳覆蓋 GitHub Pages

1. 開啟 https://github.com/cscins3/npiq-summary-test-version
2. 確認位於 `main` 分支，選擇 **Add file → Upload files**。
3. 解壓縮封包，將根目錄的 `index.html` 拖曳上傳；`README.md` 可一併上傳。
4. 選擇 **Commit changes**，等待 GitHub Pages 更新。
5. 重新整理 https://cscins3.github.io/npiq-summary-test-version/；若仍看到舊版，請強制重新整理。

請先解壓縮再上傳，不要直接將 ZIP 當成網頁檔案上傳。`index.html` 必須放在儲存庫根目錄，才能直接覆蓋目前頁面。

Copy Report 在 GitHub Pages 的 HTTPS 環境可使用瀏覽器剪貼簿功能；若瀏覽器阻擋權限，畫面會提示改為手動複製 Summary Output。

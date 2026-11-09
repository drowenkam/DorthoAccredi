# SJTU–HKIO accreditation review website

Open `index.html` after extracting the complete ZIP. Keep `assets/`, `docs/` and `data.js` beside it. No build, login or external CDN is required. The bundled SheetJS reader supports Excel import. The site does not send imported files to a server.

For GitHub Pages: upload the contents of this folder to the repository root, enable Pages for the chosen branch and root folder, and open the resulting URL. Do not upload only the ZIP. All individual PDFs and the Word/Excel downloads are in `docs/`.

## Updating

1. Edit the master Excel workbook. Preserve worksheet names, header rows and IDs. Use the dropdown statuses. Fill owner, due date, evidence link, reviewer and approval date. Record changes on the last tab.
2. In the website select **Files & updates**, import the saved `.xlsx`, then check **Action tracker** and **Workbook views**.
3. Export `data.js`. Replace the repository's `data.js` and its downloadable workbook in `docs/`. Commit both together. A browser import alone is not a shared update.
4. Word/PDF and narrative pages remain at version 1.0 until regenerated from the new approved evidence. Return the workbook and evidence for a coordinated revision.

Status **Approved** does not mean RCSEd accreditation. The verified-closure count also requires evidence, reviewer and approval date. Not-applicable decisions need documented justification and remain visible.

This package contains proposed application material only. Original reference documents are not redistributed. Keep identifiable patient records, private faculty material and confidential evidence outside public GitHub Pages. Use controlled team storage for those files. Publishing this site provides no access control.

## 繁體中文

解壓整個ZIP後開啟 `index.html`，保留 `assets/`、`docs/`及`data.js`相對位置。無須建置、登入或外部CDN。網站不會把匯入檔案上傳伺服器。

GitHub Pages：將本資料夾內容放到儲存庫根目錄，在Pages選擇相應分支及根目錄，再開啟產生的網址。不要只上傳ZIP。所有獨立PDF與Word／Excel均在`docs/`。

更新流程：編輯主Excel及最後Changes頁 → 在「檔案及更新」匯入 → 檢查工作進度及工作簿內容 → 匯出data.js → 同時替換GitHub的data.js及docs/內工作簿。瀏覽器匯入本身不會與他人同步。

Word／PDF及正文仍維持第一版，須依新核准證據重新產生。請提供更新工作簿及證據以同步修訂。「已批准」不代表RCSEd認證；核實結案還須證據、審閱人及批准日期。不適用項目須記錄理據並保留。

本套件只含建議申請內容，未再分發原參考文件。可識別病例、私人師資資料及保密證據不得放在公開GitHub Pages，應另存受控位置。本靜態網站不提供存取權限控制。

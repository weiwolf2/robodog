# 四足機器人初模 Review

這是可直接部署到 GitHub Pages 的靜態網站包。

## 檔案

- `index.html`：互動式 3D Review 頁面，模型資料已內嵌，可離線開啟。
- `quadruped_initial.stp`：頁面中的 STEP 下載檔。
- `preview_sheet.jpg`：四視角靜態預覽。
- `.nojekyll`：避免 GitHub Pages 使用 Jekyll 處理網站。

## 發布到 GitHub Pages

1. 建立一個 GitHub repository。
2. 將本資料夾內的全部檔案上傳到 repository 根目錄。
3. 在 repository 的 **Settings → Pages** 中，選擇 **Deploy from a branch**。
4. 選擇 `main` branch 與 `/ (root)`，再按 **Save**。
5. 等候 GitHub 顯示網站網址。

請保留 `index.html` 與 `quadruped_initial.stp` 在同一層，頁面中的下載按鈕才能正常使用。

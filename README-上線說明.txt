UniNotes 網站上線方式

1. 解壓縮此 ZIP。
2. 開啟 GitHub 儲存庫：https://github.com/Chen56223/piyan7
3. 點選 Add file → Upload files。
4. 將 index.html 與 .nojekyll 上傳到儲存庫最外層（與 README.md 同一層）。
5. Commit changes。
6. 到 Settings → Pages，確認 Build and deployment 的 Source 為 Deploy from a branch。
7. Branch 選 main，資料夾選 /(root)，按 Save。
8. 等待 GitHub Pages 部署完成，再開啟：https://chen56223.github.io/piyan7/

網站包含首頁、四大分類、文章閱讀頁、關鍵字搜尋與關於頁。
目前先附上 4 篇示範文章；之後可在 index.html 的 posts 陣列中增加文章。
此版本是純靜態網站，不需要 npm install 或 Astro build。

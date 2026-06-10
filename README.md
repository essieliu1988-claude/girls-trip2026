# 2026 關西名古屋 9日親子遊網頁

這是一個可放在 GitHub Pages 上使用的親子旅遊行程網頁，包含行程總覽、預算勾選、妡羽任務、歆霏注音任務與旅遊印章蒐集。

## 檔案說明

建議上傳到 GitHub 的主要檔案：

- `index.html`：主網頁檔案。請將 `japan_trip_2026_github_pages_local_save.html` 重新命名為 `index.html` 後上傳。
- `README.md`：本說明檔。

如果要讓注音字型顯示更完整，也可以一起上傳以下字型檔：

- `BpmfGenSenRounded-R.ttf`
- `BpmfGenSenRounded-M.ttf`
- `BpmfGenSenRounded-B.ttf`
- `BpmfIansui-Regular.ttf`

若沒有上傳字型檔，網頁仍可開啟，只是會改用系統預設字體。

## GitHub Pages 上傳方式

1. 建立一個新的 GitHub Repository。
2. 將修正版 HTML 檔案改名為 `index.html`。
3. 上傳 `index.html` 與 `README.md`。
4. 到 Repository 的 **Settings**。
5. 點選 **Pages**。
6. Source 選擇 **Deploy from a branch**。
7. Branch 選擇 `main`，資料夾選擇 `/root`。
8. 儲存後等待 GitHub Pages 產生網址。

## 照片與任務儲存說明

本網頁使用瀏覽器本機儲存功能保存資料。

可以保存的內容包括：

- 妡羽任務完成狀態
- 妡羽任務照片
- 預算勾選狀態
- 歆霏印章蒐集狀態
- 歆霏注音任務完成狀態

## 重要注意事項

照片與勾選資料是存在「使用者自己的手機或電腦瀏覽器」裡，不會上傳到 GitHub，也不會同步到其他裝置。

例如：

- 妡羽用自己的 iPhone 拍照，照片只會留在妡羽那台 iPhone 的瀏覽器裡。
- 媽媽用另一台手機打開同一個網址，不會看到妡羽拍的照片。
- 如果清除瀏覽器資料、換瀏覽器、開無痕模式，已儲存的照片與勾選可能會消失。

## 適合使用方式

建議讓每個孩子固定使用同一台手機或平板開啟網頁，這樣任務紀錄與照片比較不容易遺失。

如果需要多人同步、媽媽也能看到孩子拍的照片，就需要另外串接雲端資料庫或上傳服務，例如 Firebase、Supabase、Google Drive API 等。

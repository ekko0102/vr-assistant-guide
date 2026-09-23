# VR 跟隨助教測試教學網站

繁體中文操作教學：固定提示詞、JSON響應格式、17回合模擬互動，以及VR前端字幕示意。

## 發布到 GitHub Pages

將本目錄內容放在儲存庫根目錄，首頁必須是 index.html。
在儲存庫 Settings → Pages，選擇 Deploy from a branch，分支 main，目錄 / (root)，儲存後等待發布。

這是靜態教學網站，不會呼叫OpenAI API，不需要API金鑰。回覆均為示範，非實測結果。

## 檔案

- index.html：網站首頁，含完整教學。
- 01–06 JSON：設定、教材與測試紀錄範本。
- turns/：17回合的輸入、回覆示範與狀態說明。
- 00_操作手冊.html：保留離線操作手冊。

若在GitHub Free帳戶使用Pages，請使用公開儲存庫。發布後教學內容可由網站訪客閱讀。

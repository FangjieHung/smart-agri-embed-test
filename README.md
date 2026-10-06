# smart-agri-embed-test

smart-agri M5a（#205）官網嵌入的驗收用頁面，模擬客戶官網，部署在 GitHub Pages：
`https://fangjiehung.github.io/smart-agri-embed-test/?api=https://<通道>.trycloudflare.com&assistant=<助理 id>`

- 只接受 `https://*.trycloudflare.com` 的 API 位址與 GUID 格式的助理 id，不會載入其他來源的腳本。
- 頁面沒有任何金鑰。驗收結束後可封存或刪除這個 repo。

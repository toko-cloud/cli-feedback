# toko CLI Feedback

這個 repository 收集 [toko CLI](https://www.npmjs.com/package/@toko-cloud/cli) 的問題回報與功能需求。

## 提交回報

- [回報 bug](https://github.com/toko-cloud/cli-feedback/issues/new?template=bug_report.md)：自動加上 `bug` label。
- [提出功能需求](https://github.com/toko-cloud/cli-feedback/issues/new?template=feature_request.md)：自動加上 `enhancement` label。

選擇範本，補上描述，再檢查完整內容後送出。提交 issue 需要 GitHub 帳號，帳號名稱會公開顯示。

支援回報功能的 CLI 版本也可使用 `toko feedback bug` 或 `toko feedback feature` 準備回報。
CLI 會先顯示預覽，取得確認後才開啟 GitHub 草稿。請在 GitHub 編輯內容，再確認送出。
`--no-browser` 或 `--json` 只輸出草稿，不會開啟瀏覽器或建立 issue。

## 公開資料與隱私

所有 issue 都是公開的。請勿提供：

- 密碼、API key、token、cookie 或環境變數。
- 租戶名稱、租戶網址、內部網址或本機檔案路徑。
- 真實姓名、email、電話、證件、銀行資料或訂單內容。
- 未檢查的 log、完整命令參數、request／response body 或截圖。

請用假資料描述重現步驟，例如 `customer@example.com`。
CLI 自動附帶的診斷資料只限版本、OS／架構、已知命令名稱與受控錯誤分類。
自行補充的文字仍需人工檢查。移除診斷資料中的敏感資訊不代表匿名回報。

## 安全問題

請勿在這裡公開漏洞細節或憑證。請透過原有的 toko 支援管道聯絡維護者。

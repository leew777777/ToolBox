# ToolBox

小工具集合，每個工具都是純前端網頁，不需安裝或後端，下載後用瀏覽器開啟即可使用。

## 工具列表

| 工具 | 路徑 | 說明 |
|---|---|---|
| QR Code 產生器 | [`qrcode/index.html`](qrcode/index.html) | 輸入網址或文字，即時產生 QR Code，可加標題並下載 PNG |

## QR Code 產生器

- 左邊輸入網址或文字（可多行），右邊即時顯示 QR Code。
- 支援中文（內容會先轉成 UTF-8 再編碼）。
- 可選填標題，顯示在圖的上方；未輸入標題時圖為正方形。
- 圖片本身帶白邊，下載的 PNG 為高解析度（純 QR Code 640 × 640 px）。
- 下載檔名格式：`yyyy_MMdd_HHmm_標題.png`（未輸入標題則為 `qrcode`）。
- 糾錯等級為 M。

### 使用方式

下載整個 `qrcode` 資料夾（需保留 `lib` 子資料夾），用瀏覽器開啟 `index.html`。

## 使用的第三方函式庫

放在 `qrcode/lib/`：

- [jQuery](https://jquery.com/) 4.0.0（MIT）
- jquery.qrcode（MIT）

## 授權

[MIT License](LICENSE)

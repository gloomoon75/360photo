# ☁️ 360° 全景小窩

> 作者：懶人阿暝

一個打開就能用的小工具：上傳一張 360° 全景圖，畫面就會自動環繞旋轉，還能一鍵錄成影片下載。
整個工具只有一個 HTML 檔，不用安裝、不用註冊，相片也只在你自己的瀏覽器裡處理，不會上傳到任何伺服器。

![360° 全景小窩使用教學](docs/全景小窩教學_01.png)

---

## ✨ 功能

- 🖼️ **全景瀏覽**：支援 JPG / PNG 格式的 360° 全景圖（equirectangular，寬高比 2:1）
- 🌀 **自動旋轉**：可以開關，轉速可以在 -5 到 5 之間調整，設成負數就會反方向轉
- 🖐️ **自由看四周**：拖曳滑鼠或手指可以轉動視角，滾輪或雙指可以縮放
- 📐 **畫面比例**：滿版、16:9（1920×1080）、9:16（1080×1920）、1:1（1080×1080）
- 🎬 **一鍵錄影**：可以錄 1 到 60 秒，時間到會自動下載影片（mp4 或 webm）

## 🚀 使用方式

### 方法一：直接打開
1. 下載 `index.html`
2. 用瀏覽器打開（建議用最新版的 Chrome、Edge 或 Safari）

### 方法二：GitHub Pages 線上版
在 repo 的 **Settings → Pages** 裡，把 Source 設成 `main` branch，就能得到一個可以分享的網址。

> ⚠️ 需要連上網路，因為工具會從 CDN 載入 Three.js 和 Tailwind CSS。

## 🎨 沒有全景圖？用 AI 生一張

用 GPT 之類的 AI 生圖工具，在提示詞最後加上這串關鍵字：

```
360 equirectangular panorama
```

範例：

```
畫一座漂浮在雲上的夢幻遊樂園，360 equirectangular panorama
```

生成的圖是一張橫向長條（寬高比 2:1），下載後直接上傳到工具就可以用。

## 📖 操作步驟

| 步驟 | 說明 |
| --- | --- |
| 1. 準備全景圖 | 用相機拍攝，或用 AI 生成 |
| 2. 上傳相片 | 按「選擇相片」 |
| 3. 調整視角 | 拖曳旋轉、滾輪縮放 |
| 4. 選畫面比例 | 做手機直式短影音就選 9:16 |
| 5. 錄影 | 設定秒數，按「錄影」，時間到會自動下載 |

### 💡 小提醒
- 錄影時**不要切換分頁**，也不要縮小視窗，不然畫面可能會卡住
- 轉速設在 0.5 到 2 之間，看起來最舒服
- 全景圖的解析度越高，放大後越清晰
- 影片格式依瀏覽器而定：Safari 大多是 mp4，Chrome 大多是 webm

---

## 📜 授權條款：禁止商業使用

本專案（程式碼、介面設計、教學圖片）採用
**[創用 CC 姓名標示-非商業性 4.0 國際授權條款（CC BY-NC 4.0）](https://creativecommons.org/licenses/by-nc/4.0/deed.zh-hant)**。

[![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightblue.svg)](https://creativecommons.org/licenses/by-nc/4.0/deed.zh-hant)

### ✅ 你可以
- **個人使用**：自己用工具做影片、分享自己的作品
- **學習、教學使用**：拿來研究程式、在課堂上示範
- **修改和再分享**：Fork、改造，再免費公開分享

### ❌ 你不可以
- **販售**本工具，或修改過的版本
- 把本工具**付費提供**給別人使用，例如付費網站、付費會員、付費課程的教材
- 把本工具**包裝成商業產品或服務**的一部分
- 把本工具拿去**接案、代工**，向客戶收取費用
- **移除作者標示**，或宣稱是自己的作品

### 📌 使用時請標示
轉載、修改或分享時，請保留作者標示並附上原始連結，例如：

```
原作者：懶人阿暝 ｜ 360° 全景小窩
https://gloomoon75.github.io/360photo/
```

## 🧩 使用的第三方套件

以下套件各自依照它們原本的授權條款使用，不受本專案授權條款的限制：

- [Three.js](https://github.com/mrdoob/three.js)：MIT License
- [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss)：MIT License
- [Zen Maru Gothic](https://fonts.google.com/specimen/Zen+Maru+Gothic)：SIL Open Font License 1.1

---

Made with ☁️ by **懶人阿暝**

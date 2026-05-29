# NEURAL INTERACTION INTERFACE // 智慧終端控制台

這是一個具備未來科幻視覺風格（Cyberpunk / Hologram 終端機風格）的純前端單網頁應用程式。

## 🚀 快速開始

本專案所有的 HTML、CSS 和 JavaScript 已全部整合至一個單一檔案中。

### 開啟方式
1. 直接在檔案總管中雙擊開啟 **[index.html](index.html)** 檔案。
2. 或是使用任何網頁瀏覽器（如 Chrome、Edge、Firefox）直接將該檔案拖曳進去即可運行。

---

## ⚡ 核心功能與特效

### 1. 科技感視覺美學
* **動態網格背景 (Grid Pattern)**: 背景使用動態 CSS 線性漸層繪製的細緻網格，增強數位空間感。
* **CRT 螢幕掃描線 (Scanlines Overlay)**: 疊加了動態垂直微影掃描效果，還原復古未來主義（Retro-futurism）終端質感。
* **霓虹發光氣氛燈 (Neon Glow Orbs)**: 左右兩側設計有流動飄浮的青藍與洋紅發光球體（Glow Orbs），形成和諧的霓虹色調。
* **玻璃擬態 (Glassmorphism)**: 卡片主體採用高毛玻璃模糊度與半透明發光邊框，創造出懸浮的全息投影效果。

### 2. 微互動體驗
* **3D 卡片立體懸浮 (3D Parallax Tilt)**: 頁面會偵測滑鼠位置，讓主終端卡片隨著游標的移動產生細微的 **3D 旋轉傾斜視差**，使卡片立體感十足。
* **終端機打字機效果 (Advanced Typewriter)**: 點擊確認或按下 `Enter` 鍵送出名稱後，下方的輸出日誌（Output Log）會以科幻終端機讀取文字的方式，逐字動態印出結果。
* **安全資料處理**: 系統內建 HTML 轉義機制，防止輸入內容造成 XSS (跨網站指令碼) 注入漏洞。

### 3. 即時音效合成器 (Web Audio API)
* 完全無須加載外部 `.mp3` 或 `.wav` 音訊檔案。
* **打字聲 (Tap Sound)**: 輸入欄位輸入內容時，會即時透過程式碼合成器發出清脆的電子按鍵嗶嗶聲。
* **驗證成功 (Success Chime)**: 送出驗證名稱後，會合成本調式的雙音和弦提示音。
* **驗證失敗 (Error Buzz)**: 輸入空白或無效字元時，會發出鋸齒波合成的低音警告蜂鳴聲。
*(註：因瀏覽器安全性限制，音效會在使用者與頁面進行首次互動（點擊或打字）後自動激活。)*

---

## 🛠️ 技術堆疊
* **結構**: HTML5 (語意化標籤)
* **視覺**: Vanilla CSS3 (自訂變數, Flexbox, Keyframe 動態, Backdrop-filter 模糊)
* **邏輯**: Vanilla JavaScript (ES6+, Web Audio API, DOM 操作)
* **字型與圖標**: 
  * Google Fonts: Orbitron & Rajdhani
  * FontAwesome 6.4 (科幻圖標)

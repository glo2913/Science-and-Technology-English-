# ⚡ 科技英文背單字網站 (TechVocab Master)

這是一個專為學習科技英文設計的互動式背單字 Web 應用程序。透過簡潔的介面與多樣化的複習模式，幫助使用者更有效率地掌握專業詞彙。

## 🌟 核心特色

- **多維度複習模式**：
  - `依序複習`：按照課程進度穩紮穩打。
  - `隨機挑戰`：打破記憶規律，強化實戰能力。
  - `20題測驗`：適合零碎時間的快速自我檢測。
  - `收藏模式`：針對弱點單字進行重點突破。
- **沉浸式學習體驗**：
  - **三種視覺主題**：支援「極簡家居」、「深色模式」及「遊戲化模式」。
  - **發音功能 (TTS)**：整合瀏覽器 Web Speech API，即時點擊即時發音。
  - **快捷鍵操作**：支援空白鍵、方向鍵與 R/S 鍵，提升學習流暢度。
- **數據持久化**：使用 `LocalStorage` 紀錄使用者收藏的單字與偏好主題，下次開啟免設定。
- **動態數據載入**：利用 `PapaParse` 解析 CSV 檔案，方便擴充教材內容。

## 🛠️ 技術棧 (Tech Stack)

- **Frontend**: HTML5, CSS3 (Flexbox/Grid, Glassmorphism), JavaScript (ES6+)
- **Libraries**:
  - [PapaParse](https://www.papaparse.com/): 高效解析單字 CSV 數據。
  - [Canvas-confetti](https://www.npmjs.com/package/canvas-confetti): 遊戲模式下的視覺特效反饋。
- **Web APIs**: Web Speech API (TTS), LocalStorage.

## 📸 功能展示

| 模式 | 描述 |
| --- | --- |
| **主題切換** | 支援🌙深色、🏠預設、🎮遊戲三種模式隨時切換。 |
| **單字卡片** | 採用玻璃擬態 (Glassmorphism) 設計，支援星號收藏與例句顯示。 |
| **Combo 系統** | 在遊戲模式下連續答題會觸發特效，增加學習樂趣。 |

## 🚀如何運行

1.  使用 VS Code 開啟此專案資料夾。
2.  啟動 **Live Server** 插件運行 `index.html`。

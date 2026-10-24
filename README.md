# 紅焰 - AI 備課自動化工作流 (AI Lesson Preparation Autoflow)

專為教育工作者設計的教學指南與簡報互動系統。結合 Google 生態系的五大 AI 工具，將備課流程系統化。透過清晰的提示詞與操作步驟，打造專屬 AI 助教團隊。

- **來源網站**：[Google 協作平台 - AI 備課自動化工作流](https://sites.google.com/view/prepareautoflow/)
- **展示主題**：從發想到自動化的教學金字塔

---

## 核心架構：五大工具層次定位

1. **L1 靈感層：Ask Gemini**  
   - Chrome 內建 AI 側邊欄助理，免切換分頁直接讀取當前資訊。  
   - 適合摘要、多資料統整與跨應用協作。

2. **L2 模組層：Gems**  
   - 封裝特定 Prompt 與知識庫的專屬教學助教。  
   - 適合固定格式重複性產出（如素養導向學習單產生器）。

3. **L3 擴充層：Skill**  
   - 具備邏輯判斷與程序步驟的結構化運算外掛。  
   - 鎖定演算邏輯，精準輸出教案與雙向細目表。

4. **L4 生產層：Spark (任務)**  
   - 跨越「對話文字」到「雲端實體檔案」的自動化生產引擎。  
   - 一鍵轉為 Google Docs 教案、Google Slides 簡報與評量資源。

5. **L5 系統層：Workspace**  
   - 觸發式與跨服務的教學行政整合中樞。  
   - 打造無人值守工作流（表單提交 → AI 批改 → 文件歸檔 → 自動寄信）。

---

## 功能亮點

- 🖥️ **響應式互動簡報**：全螢幕高畫質呈現 10 個核心章節與教學提示詞。
- ⌨️ **鍵盤與點擊導航**：支援鍵盤左右鍵、空白鍵快速切換，手機與平板點擊兩側切換。
- 📋 **一鍵複製提示詞**：內建模擬點擊複製與 Toast 動態提示，即點即用。
- ⚡ **純前端零依賴**：基於 HTML5 + Tailwind CSS + Google Material Icons，載入極速。

---

## 部署說明

### Netlify 部署
1. 登入 [Netlify](https://app.netlify.com/)
2. 點擊 **Add new site** -> **Import an existing project** -> 選擇 GitHub 倉庫 `prepareautoflow`
3. 發布目錄（Publish directory）設定為 `.`
4. 點擊 **Deploy site** 即可完成上線！

### GitHub Pages 部署
1. 進入本倉庫 Settings -> **Pages**
2. Build and deployment 的 Source 選擇 **Deploy from a branch**
3. Branch 選擇 `main` / `root`
4. 點擊 Save，幾分鐘後即可透過 `https://<username>.github.io/<repo>/` 訪問。

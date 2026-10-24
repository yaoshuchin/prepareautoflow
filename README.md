# 紅焰 - AI 備課自動化工作流與 1024 研習資料全集 (AI Lesson Preparation Autoflow)

專為教育工作者設計的教學指南、互動簡報與實戰提示詞庫系統。

結合 Google 生態系的五大 AI 工具（Ask Gemini、Gems、Skill、Spark、Workspace），並完整收錄 **1024「紅焰」研習** 所涵蓋的「備課資源、AI 教學技能、資訊自動化、每日 AI 教育簡報、Gem 轉換 Skill、AI 閱卷評量」六大類應用。

- **線上瀏覽 (GitHub Pages)**：[https://yaoshuchin.github.io/prepareautoflow/](https://yaoshuchin.github.io/prepareautoflow/)
- **原始來源**：[Google 協作平台 - AI 備課自動化工作流](https://sites.google.com/view/prepareautoflow/)

---

## 雙模式切換特色

### 1. 🎓 金字塔簡報模式 (10 頁投影片)
- **L1 靈感層：Ask Gemini**（側邊欄提問、跨分頁比價、跨應用 Gmail 寄件）
- **L2 模組層：Gems**（人設與固定任務封裝、學習單產生器）
- **L3 擴充層：Skill**（邏輯判斷與程序步驟、教案與雙向細目表精準矩陣運算）
- **深度解析**：Gems vs Skill 決定性差異對照
- **L4 生產層：Spark (任務)**（文字轉為 Google Docs、Slides、知識結構圖與 Kahoot 試算表實體雲端歸檔）
- **L5 系統層：Workspace**（觸發式與跨服務無人值守工作流）
- **核心差異**：Spark vs Workspace 兵工廠與流水線對照

### 2. 📚 1024 紅焰研習全集與提示詞庫
- **一、研習主題與重要資源**：協作平台、Padlet 研習板、Fire Skills 指令集、Gem Skills、閱讀教學資源與購物比價範例。
- **二、國小四年級「媒體識讀」課程資源生成**：串聯 `@tw-spark-edu-lesson-plan`、`@tw-spark-edu-rubric-designer`、`@interactive-website-generator`（蒙德里安風格）與全套備課資源包。
- **三、YouTube 資訊匯流中心：Notion 自動更新**：使用 `@youtube-rss-to-notion` 定時檢查 4 大優質頻道並同步至 Notion。
- **四、台股開盤前脈動報告**：美股四大指數、費半、TSM ADR、台指期夜盤與開盤預估提示詞。
- **五、Gmail 自動記帳**：掃描過去一週帳單、水電、發票與刷卡通知，結構化寫入 Google 試算表。
- **六、每日 AI 教育簡報與深度分析報告**：產出 8 頁 Slides、Docs 深度報告並自動寄送至 `todoharp2010@gmail.com`。
- **七、Gemini GEM 轉換為 SKILL 完整規範**：備份 GEM 為標準 `SKILL.md`，保留 `references/` 並打包 ZIP。
- **八、AI 閱卷評閱專家：媒體識讀簡答題評量**：五大核心向度標準化計分（誤差小於 3 分）、雷達圖與鷹架引導。
- **九、待補資料與後續執行清單**：內建互動式 Checkbox，即時追蹤完成進度並自動儲存至 LocalStorage。

---

## 快捷操作說明

- **切換模式**：點擊頂部導航列之 `[金字塔簡報]` 或 `[1024 研習全集]` 隨時無縫切換。
- **簡報鍵盤控制**：支援 `←`、`→`、`Space` 鍵快速翻頁。
- **一鍵複製提示詞**：所有實戰提示詞均提供「📋 複製提示詞」按鈕，點擊後會顯示綠色 Toast 提示並寫入系統剪貼簿。
- **待辦互動勾選**：清單勾選狀態自動儲存於瀏覽器，進度條動態計算百分比。

---

## 部署說明

### Netlify 部署
1. 登入 [Netlify](https://app.netlify.com/)
2. 點擊 **Add new site** -> **Import an existing project** -> 選擇 GitHub 倉庫 `prepareautoflow`
3. 發布目錄（Publish directory）設為 `.`（已由 [netlify.toml](file:///c:/antigravity/1151024紅焰AI/netlify.toml) 自動配置）
4. 點擊 **Deploy site** 即可完成上線。

### GitHub Pages
- 已自動配置啟用：[https://yaoshuchin.github.io/prepareautoflow/](https://yaoshuchin.github.io/prepareautoflow/)


* **創作者 (Author):** [歐志賢 (Andy Ou) - 15 年 IT 資訊人與 15 年木工職人雙重背景](https://www.liying.tw/andy-ou-dr-oh-google-ai-search-black-box-research-l001/)。

# A Cost-Driven Resource Allocation Model for Google AI Search (AIO)

This repository contains the core frameworks for understanding Google AI Overviews (AIO) and AI Mode through the lens of resource allocation, query depth, and sufficient source selection. 
本專案開源釋出 Google AI Search（AIO / AI Mode）的底層資源配置、查詢深度與來源選擇框架。

## 📌 Temporal Priority & Provenance (時間優先權與來源證明)
The core concepts, definitions, and models in this repository were originally published and timestamped by Andy (liying.tw) on LinkedIn between August 29 and September 4, 2026.
本框架之核心變數設計與實證模型，最早於 2026 年 8 月至 9 月間於 LinkedIn 完成時間戳記與公開發布。

* **Phase 1 (L-800):** [View Original LinkedIn Timestamp](https://www.linkedin.com/feed/update/urn:li:activity:7500566886212849664/)
* **Phase 2 (L-801):** [View Original LinkedIn Timestamp](https://www.linkedin.com/feed/update/urn:li:activity:7500902504558129152/)
* **Phase 3 (L-802):** [View Original LinkedIn Timestamp](https://www.linkedin.com/feed/update/urn:li:activity:7501626733134163968/)

## 📖 Framework Structure (雙語框架綱要)

### 1. The Evidence Layer / 決策證據層 (L-800 / L-808)
* **Focus:** Transforming First-Hand Expertise into machine-readable decision variables.
* **核心機制：** 將第一手經驗轉化為 AI 可提取的決策變數（正向證據、負向證據、邊界條件、失敗情境），取代單純的字數擴充與商品化內容。

### 2. Query-time Source Selection / 查詢時來源選擇 (L-801 / L-809)
* **Focus:** Query Depth → Required Source Depth → Sufficient-source Selection.
* **核心機制：** Google AIO 依據「查詢深度」決定「所需來源深度」。以最低必要運算成本完成「充分來源選擇」，而非盲目抓取最高權威網站。

### 3. Pre-query Resource Allocation / 查詢前資源配置 (L-802 / L-810)
* **Focus:** Past Information Value → Expected Source Value → Processing Priority.
* **核心機制：** 資源配置模型。高價值內容（Information Gain）將獲得較高的預期來源價值，從而在非同步的處理管線（Pipeline）中取得優先權。

## 🔗 Primary Evidence & Commercial Case Studies (完整圖文實測證據)
This repository serves as the structural framework. For full experimental logs, GSC crawl dependencies, and real-world woodworking/clinical case studies, please refer to the primary research domain:
本開源專案僅提供理論骨架。包含完整時間對照、GSC 檢索軌跡與真實木工實驗（Woodworking Case Study）的圖文觀測日誌，請以主網域發布之內容為準：

* **English Deep Research:** [Google AI Search & AIO Case Studies (liying.tw)](https://www.liying.tw/first-hand-expertise-google-ai-search-woodworking-case-study-l800/)
* **繁體中文深度實驗：** [Google AI 搜尋黑箱拆解與實證 (liying.tw)](https://www.liying.tw/google-ai-search-real-world-woodworking-experiments-l808/)


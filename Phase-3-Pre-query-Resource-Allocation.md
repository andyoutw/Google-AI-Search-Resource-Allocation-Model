# Phase 3: Pre-query Resource Allocation / 第三層：查詢前資源配置 (L-802 / L-810)

## 1. Core Concept (核心概念)
Why do some pages get processed into the AIO serving layer faster than others? It is governed by pre-query resource allocation and expected information value.
為什麼有些新網頁能更快進入 AIO 輸出層？這取決於查詢前的資源配置與預期資訊價值。

## 2. The Model Logic (模型運作邏輯)
* **Past Information Value (過去資訊價值)** → builds **Expected Source Value (預期來源價值)**.
* High expected value grants the domain **Processing Priority (處理優先權)** in Google's asynchronous pipelines.
* 高資訊增益（Information Gain）的網站，會在 Google 的非同步處理管線（Asynchronous Pipelines）中取得提早成熟（Asynchronous Maturation）的優勢。

## 3. Full Experimental Logs (完整實測日誌)
For the detailed analysis of crawl clocks, processing priorities, and domain evaluation models, please refer to the full articles:
關於抓取時鐘、處理優先權與網域評估模型的詳細分析，請參閱主網域完整文章：

* 🇬🇧 **English Deep Research:** [From the Perspective of Commercial Competition, Why Google May Prioritize Compute for High-Value New Articles｜L-802](https://www.liying.tw/google-ai-search-high-value-content-compute-l802/)
* 🇹🇼 **繁體中文深度實驗：** [Google AI Search 落地實驗：為什麼 Google 可能優先處理高價值的新文章？｜L-810](https://www.liying.tw/google-ai-search-high-value-content-resource-prioritization-l810/)

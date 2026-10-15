# Phase 2: Query-time Source Selection / 第二層：查詢時來源選擇 (L-801 / L-809)

## 1. Core Concept (核心概念)
Google AIO does not always select the "deepest" or "most authoritative" source. Instead, it follows a cost-driven model based on the query's complexity.
Google AIO 不一定選擇「最深」或「權威最高」的來源，而是基於運算成本與查詢複雜度進行分配。

## 2. The Model Logic (模型運作邏輯)
* **Query Depth (查詢深度)** → determines the **Required Source Depth (所需來源深度)**.
* **Low-cost Sufficient Source Selection (低成本充分來源選擇)**: AIO will select the source that requires the least compute power to fulfill the semantic requirement.
* AIO 會選擇「能滿足語意需求且運算成本最低」的來源，而不是盲目抓取最長的文章。

## 3. Full Experimental Logs (完整實測日誌)
To see how different query depths trigger different source selections in real time, please refer to the full articles:
關於「不同查詢深度如何觸發不同來源選擇」的即時觀測證據，請參閱主網域完整文章：

* 🇬🇧 **English Deep Research:** [A Cost-Driven Resource Allocation Model for Google AI Search: Query Depth and Sufficient-Source Selection｜L-801](https://www.liying.tw/a-cost-driven-resource-allocation-model-for-google-ai-search-query-depth-and-sufficient-source-selection%ef%bd%9cl-801/)
* 🇹🇼 **繁體中文深度實驗：** [Google AI Search 落地實驗：為什麼資訊最多的文章，不一定被 AI 採用？｜L-809](https://www.liying.tw/google-ai-search-content-depth-source-selection-experiment-l809/)

# HEART-LAB｜最終繳交導覽

**作業主題：用 LLM Wiki 做一份教學 HTML 簡報**  
**專案名稱：HEART-LAB｜心動研究所**  
**副標題：THE PSYCHOLOGY OF FANDOM｜從心理學看追星文化**

---

## 一、主題與介紹

本專案想回答：「我們為什麼會對一個可能永遠不認識自己的人，產生這麼多情感？」

HEART-LAB 以心理學研究為基礎，主要使用 K-pop 粉絲文化作為案例，整理熟悉感與好感、擬社會互動與擬社會關係（PSI／PSR）、粉絲認同與社群歸屬、錯失恐懼（FoMO）、收藏消費，以及健康追星與心理界線。

本專案不是要判斷追星好不好，也不把追星直接視為不理性或心理問題，而是希望讓讀者理解：追星可能帶來快樂、支持與歸屬，也可能在某些情境下伴隨焦慮、群體壓力或消費風險。

## 二、成果連結

| 繳交項目 | 成果 |
|---|---|
| GitHub 專案總覽 | [HEART-LAB Repository](https://github.com/Tina710526/HEART-LAB) |
| LLM Wiki 知識頁 | [02_KNOWLEDGE 知識庫](https://github.com/Tina710526/HEART-LAB/tree/main/02_KNOWLEDGE) |
| 教學 HTML 簡報 | [開啟 18 頁互動簡報](https://tina710526.github.io/HEART-LAB/#slide-1) |
| 知識地圖 | [KNOWLEDGE_MAP.md](04_KNOWLEDGE_GRAPH/KNOWLEDGE_MAP.md) |
| 概念關係圖 | [CONCEPT_RELATIONS.md](04_KNOWLEDGE_GRAPH/CONCEPT_RELATIONS.md) |
| 來源匯入紀錄 | [INGEST_REPORT.md](05_QUALITY_CONTROL/INGEST_REPORT.md) |
| LLM 討論與修訂紀錄 | [LLM_DISCUSSION_AND_GENERATION_LOG.md](07_ASSIGNMENT/LLM_DISCUSSION_AND_GENERATION_LOG.md) |
| Loop／Graph 流程與反思 | [LLM_WIKI_WORKFLOW.md](07_ASSIGNMENT/LLM_WIKI_WORKFLOW.md) |
| 教學內容查核 | [TEACHING_CONTENT_CHECK.md](05_QUALITY_CONTROL/TEACHING_CONTENT_CHECK.md) |
| HTML 實測紀錄 | [HTML_IMPLEMENTATION_QA.md](05_QUALITY_CONTROL/HTML_IMPLEMENTATION_QA.md) |

## 三、Wiki 建置成果

- 正式來源共 **13 筆（S001–S013）**。
- **12 筆全文已核對**；S003 已取得完整論文，但只核對與本專案主張直接相關的核心章節，因此獨立標示。
- 目前有 **11 頁 Wiki 知識頁**，依主題分為心動的開始、想像中的連結、我們的粉絲宇宙、喜歡的代價、如何好好地喜歡。
- 每筆來源紀錄盡可能保留作者、年份、研究目的、研究類型、樣本、方法、主要發現與限制。
- 知識地圖把來源連到知識頁，再連到教學主題；概念箭頭代表整理後的概念關聯或教學順序，不表示所有關係都已被研究證明為因果。

### 資料到知識的例子

| 來源 | 轉化後的 Wiki 主題 |
|---|---|
| S010 | 單純接觸效應、熟悉感與好感的可能關係 |
| S001、S008 | PSI／PSR 的概念差異與媒體互動情境 |
| S002、S007、S009 | 粉絲認同、社群互動與歸屬感 |
| S004、S005、S006 | FoMO 的概念、粉絲經驗與網路使用 |
| S003、S012、S013 | 小卡收藏、周邊稀缺感、FoMO 與購買動機 |
| S001、S003、S004、S006、S007、S008、S012、S013 | 研究方法、樣本限制與證據判讀 |

## 四、教學 HTML 簡報

簡報共 **18 頁**，依照初學者的理解順序，從個人經驗開始，再進入心理學概念、粉絲社群、可能壓力、研究判讀與健康追星。

主要功能：
- 上一頁／下一頁與頁碼、進度同步。
- 章節選單跳轉。
- 鍵盤方向鍵、Home、End 等導覽。
- PSI／PSR 情境互動。
- 研究判讀與總複習測驗。
- 參考來源清單。
- 個人反思欄位，可輸入、複製與清除；不連接資料庫。
- 手機版版面與減少動態效果設定。

## 五、Loop／Graph 執行流程

本專案不是一次生成完成，而是採用有回饋檢查點的循環流程：

1. **資料取得**：蒐集與主題相關的研究來源。
2. **Ingest／來源紀錄**：建立 S001–S013 來源卡，整理研究資訊。
3. **來源查核**：確認作者、年份、樣本、方法、結果與研究限制。
4. **先討論、後生成**：先與 LLM 討論概念定義、研究適用範圍與教學例子，再修訂 Wiki。
5. **Wiki 交叉整理**：建立知識頁、內部連結、知識地圖與概念關係。
6. **教學規劃**：將知識重新排序為初學者能理解的教學順序。
7. **內容查核**：逐頁確認簡報主張可回到 Wiki／來源，並保留樣本及方法限制。
8. **HTML 生成**：製作 18 頁投影片與互動功能。
9. **實際測試**：操作導覽、互動題、章節選單與不同瀏覽器。
10. **修正與再測**：依問題回到來源、Wiki 或程式碼修正，再重新驗證。

### 主要回饋迴圈

- 來源不足或資訊不清楚 → 回到資料取得。
- Wiki 主張沒有來源支持或限制不清楚 → 回到討論與 Wiki 修訂。
- 投影片內容過度延伸或把相關性寫成因果 → 回到 Wiki／來源查核。
- 按鈕或回饋邏輯錯誤 → 修改 JavaScript，再重新操作測試。
- 版面問題 → 修改 CSS，再以瀏覽器確認。

完整流程圖與節點說明見 [LLM_WIKI_WORKFLOW.md](07_ASSIGNMENT/LLM_WIKI_WORKFLOW.md)。

## 六、實際執行與測試證據

### Wiki／內容查核

- 來源匯入報告記錄 13 筆來源的查核狀態；12 筆全文已核對，S003 為全文取得、核心章節核對。
- 七章教學內容已進行來源對應查核。
- 2026-11-19 再針對第 4、5、7、10、12、13 頁進行 Wiki 與簡報對應修訂／複查。
- 第 4、5 頁直播例子調整為偶像向所有觀眾說話，避免將實際留言回覆誤當成單向 PSI。
- 第 7 頁的社群壓力句子標示為生活情境示例，不包裝成 S007 的直接研究結果。
- 第 10 頁補上 S012 橫斷式問卷不能證明因果的提醒。
- 第 12、13 頁新增「研究方法與證據判讀」Wiki，補足研究方法與推論界線的知識依據。

### HTML 實作與瀏覽器測試

開發時曾發現快問快答原本只顯示相同的正向回饋，未依答題正誤區分。後續修正 JavaScript，讓答對／答錯顯示不同回饋，並在作答後鎖定該題。

使用者於 2026-11-19 回報：
- Chrome 與 Microsoft Edge 均可從第 1 頁操作至第 18 頁，完整簡報操作正常。
- Chrome Console 未看到紅色錯誤。
- Edge Console 未看到紅色錯誤。
- 第 4、5、7、10 頁修訂後顯示與操作正常。

另完成程式碼靜態檢查：18 個投影片區塊 ID 依序存在、沒有重複 HTML ID，JavaScript 取得的指定元素均存在，並確認有響應式樣式、減少動態效果與列印樣式。

**證據界線：**瀏覽器結果為使用者實際操作與查看後的回報，並非自動化瀏覽器測試。完整紀錄與各項檢查範圍見 [HTML_IMPLEMENTATION_QA.md](05_QUALITY_CONTROL/HTML_IMPLEMENTATION_QA.md)。

## 七、反思：最容易出錯的節點與流程調整

### 最容易出錯的節點

我認為最容易出錯的是「把研究內容轉成一般人看得懂的教學說法」。因為研究常有特定樣本、研究方法與限制，如果只留下結論，很容易把某一群受訪者的經驗說成所有粉絲都一樣，也可能把相關或統計中介說成因果。

另一個容易出錯的地方是互動功能。按鈕能點不代表程式回饋正確；本次快問快答就曾出現答對、答錯都顯示相同回饋的問題。

### 把檢查往前移

後續把研究樣本、方法、結果與限制的檢查提前到 Wiki 生成與簡報撰寫之前；每一個重要教學主張都要能回到來源。互動功能則不只檢查程式碼是否存在，也要實際點選並確認回饋內容。

### Workflow／Graph 的改變

一開始可以把流程想成「找資料 → 整理 → 做簡報」，但實際執行後發現，若前面的來源理解錯誤，後面的 Wiki 和投影片都會跟著錯。因此改成有多個判斷點與回頭修正的流程：來源不足就補資料、內容查核不通過就修 Wiki、互動測試失敗就修程式再測試。

這樣能讓錯誤在較早的階段被發現，也能留下每次修正的原因與依據。

## 八、研究限制與誠實揭露

- 不同來源的國家、平台、樣本與研究方法不同，不能把數字直接合併成所有粉絲的共同結果。
- S010 是一般心理學回顧，不是 K-pop 專屬研究；追星情境是教學應用例子。
- S003 雖取得完整論文，但本專案僅核對核心相關章節。
- S012 自我控制交互作用係數與作者文字解讀存在疑點，因此保留不確定性。
- 健康追星建議是依研究概念整理的實務提醒，不宣稱為單篇研究驗證的治療方案。
- GitHub Repository 是本專案 Markdown Wiki 的管理與展示位置，不宣稱它本身是獨立的 LLM Wiki 平台。

## 九、老師檢查建議順序

1. 先開啟 [教學 HTML 簡報](https://tina710526.github.io/HEART-LAB/#slide-1)，確認實際成品。
2. 再看 [02_KNOWLEDGE](https://github.com/Tina710526/HEART-LAB/tree/main/02_KNOWLEDGE)，確認 Wiki 知識頁。
3. 查看 [KNOWLEDGE_MAP.md](04_KNOWLEDGE_GRAPH/KNOWLEDGE_MAP.md) 與 [CONCEPT_RELATIONS.md](04_KNOWLEDGE_GRAPH/CONCEPT_RELATIONS.md)，確認來源、知識與概念的連結。
4. 查看 [LLM_WIKI_WORKFLOW.md](07_ASSIGNMENT/LLM_WIKI_WORKFLOW.md) 與 [LLM_DISCUSSION_AND_GENERATION_LOG.md](07_ASSIGNMENT/LLM_DISCUSSION_AND_GENERATION_LOG.md)，確認先討論後生成、Loop／Graph 與反思。
5. 最後查看 [INGEST_REPORT.md](05_QUALITY_CONTROL/INGEST_REPORT.md)、[TEACHING_CONTENT_CHECK.md](05_QUALITY_CONTROL/TEACHING_CONTENT_CHECK.md) 與 [HTML_IMPLEMENTATION_QA.md](05_QUALITY_CONTROL/HTML_IMPLEMENTATION_QA.md)，確認來源與實測紀錄。

---

**最終成果：13 筆來源、11 頁 Wiki、知識地圖與概念關係圖、18 頁互動式教學 HTML，以及實際執行、查核與反思紀錄。**

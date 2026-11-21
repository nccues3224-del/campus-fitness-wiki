# 作業繳交報告：用 LLM Wiki 製作教學 HTML 簡報

* **繳交標題格式**：`[學校] [學號] [系級] [姓名] 大學生零基礎健身通關指南`  
  *(註：請於提交時替換為個人的學校、學號、系級與姓名)*
* **作業專案目錄**：`c:\大二下\AI`

---

## 一、LLM Wiki 主題與簡短介紹

### 1. 知識庫主題
**「大學生零基礎健身通關指南 (Campus Fitness LLM Wiki)」**

### 2. 簡短介紹與受眾痛點
本知識庫專門針對「完全沒有任何健身經驗的大學生」設計。大學生在邁入運動時普遍面臨四大痛點：**預算有限（以學餐與超商外食為主）、時間破碎且易受期中期末考打亂、對重訓器材陌生害怕被看、充斥網路錯誤迷思（如極端節食、暴汗排毒等）**。

本知識庫遵循 Andrej Karpathy 的 **LLM Wiki Pattern** 構建，透過「**先討論、後生成**」的協同維護模式，在原始不可變來源層（Raw Sources）與展示交付層（HTML Slides）之間，建立一個持續複利累積、具備運動科學實證與在地校園可落地的持久化 Markdown 知識網絡。

---

## 二、LLM Wiki 成果與檔案連結

本知識庫嚴格落實 Karpathy 的三層架構：

### 1. 根目錄憲法與索引層
* [AGENTS.md](file:///c:/大二下/AI/AGENTS.md)：**知識庫憲法與運作規範（The Schema）**，定義 Agent 角色定位、語調規範、本地圖片引用標準與 Ingest / Query / Lint 標準作業程序。
* [index.md](file:///c:/大二下/AI/index.md)：**知識導航索引（The Index）**，按概念、動作、營養、減脂、課表與來源分類，提供單行摘要與雙向連結導航。
* [log.md](file:///c:/大二下/AI/log.md)：**變更日誌（The Log）**，Append-only 記錄所有資料匯入、詞條擴充與版本推進時間軸。

### 2. 原始資料來源層 (Raw Sources - 已完成 5 篇權威文獻 Ingest)
* [issn-protein-exercise-position-stand.md](file:///c:/大二下/AI/raw/issn-protein-exercise-position-stand.md)：國際運動營養學會 (ISSN) 蛋白質與運動立場聲明（確立 1.2~1.6g/kg 學生攝取量與每餐 20~40g 蛋白質上限）。
* [acsm-exercise-guidelines-resistance.md](file:///c:/大二下/AI/raw/acsm-exercise-guidelines-resistance.md)：美國運動醫學會 (ACSM) 初學者阻力訓練指引（確立每週 2~3 天全身模式與機械式器材優先原則）。
* [zone2-fat-oxidation-san-millan.md](file:///c:/大二下/AI/raw/zone2-fat-oxidation-san-millan.md)：Dr. San-Millán 粒線體功能與 Zone 2 脂肪氧化研究（確立最大脂肪氧化率 FatMax 與說話檢測法 Talk Test）。
* [energy-balance-hall-cico.md](file:///c:/大二下/AI/raw/energy-balance-hall-cico.md)：Dr. Kevin Hall 於《The Lancet》發表之能量動態平衡 CICO 與局部減脂在生理學上的否證研究。
* [taiwan-convenience-store-nutrition-db.md](file:///c:/大二下/AI/raw/taiwan-convenience-store-nutrition-db.md)：台灣 7-11 與全家超商常見高蛋白食品價格、熱量與蛋白質含量實測資料庫（計算每克蛋白質 CP 值與學生銅板組合）。

### 3. 持久化雙向連結知識庫層 (The Wiki)
* **概念庫 (Concepts)**：
  * [cico-energy-balance.md](file:///c:/大二下/AI/wiki/concepts/cico-energy-balance.md)：CICO 熱量平衡物理法則、每日 TDEE 四大構成與不吃低於基礎代謝率 (BMR) 的關鍵。
  * [zone2-cardio.md](file:///c:/大二下/AI/wiki/concepts/zone-2-cardio.md)：Zone 2 低強度心率燃脂機制、操場實踐與說話檢測法（Talk Test）。
* **訓練庫 (Training)**：
  * [four-movement-patterns.md](file:///c:/大二下/AI/wiki/training/four-movement-patterns.md)：人體四大基礎動作模式（推、拉、蹲、鉸鏈）與新手機械式器材指引。
  * [warmup-sop.md](file:///c:/大二下/AI/wiki/training/warmup-sop.md)：胸推前熱身 4 步驟 SOP（輕度有氧 ➔ 滾筒放鬆 ➔ 動態伸展 ➔ 啟動肌群）與防受傷指南。
* **營養庫 (Nutrition)**：
  * [protein-basics-and-sources.md](file:///c:/大二下/AI/wiki/nutrition/protein-basics-and-sources.md)：超商 3 大平民神隊友（無糖高纖豆漿、茶葉蛋、舒肥雞胸肉）與乳清補劑迷思破解。
* **減脂庫 (Fat Loss)**：
  * [fat-loss-myths.md](file:///c:/大二下/AI/wiki/fat-loss/fat-loss-myths.md)：擊破 3 大常見迷思（穿暴汗服狂流汗、跳過晚餐完全戒澱粉、每天做仰臥起坐瘦肚子）。
* **課表庫 (Programming)**：
  * [student-3day-split.md](file:///c:/大二下/AI/wiki/programming/student-3day-split.md)：每週 3 天全身交替課表與期中期末考週「最低維持劑量」應變策略。
* **簡報沉澱庫 (Presentation)**：
  * [campus-fitness-101-slides.md](file:///c:/大二下/AI/wiki/presentation/campus-fitness-101-slides.md)：9 頁投影片內容與底層 Wiki 知識點的雙向錨定與演講備忘沉澱。

---

## 三、教學 HTML 簡報成果連結

* [index.html](file:///c:/大二下/AI/index.html)：**大學生零基礎健身通關指南（CAMPUS FITNESS 101）**
* **簡報規格說明**：
  * **視覺風格**：Neo-Brutalism（美式潮流撞色風），採用粗黑邊框 `3.5px solid #000`、硬投影 `6px 6px 0px #000`、傾斜旋轉貼紙 Badge（如 `CAMPUS FITNESS 101`、`🧠 大腦升級外掛`）與高飽和能量配色。
  * **本地素材整合**：精準無破圖綁定同層 5 張本地圖檔（繫鞋帶起步、陽光重訓、Heho 胸推熱身 4 步驟圖解、瑜珈放鬆伸展、20 款運動圖示合集）。
  * **操作特性**：支援鍵盤左右鍵 (`←` / `→` / `Space`) 換頁、`F` 鍵全螢幕投影切換、頂部彩色漸層進度條與響應式 16:9 比例畫布。
  * **規格依據**：完整依據大綱 [outline.md](file:///c:/大二下/AI/outline.md) 與逐頁規格書 [slides-spec.md](file:///c:/大二下/AI/slides-spec.md) 生成。

---

## 四、Loop / Graph 流程設計與說明

本專案將 Karpathy 的 Wiki 模式擴展為 **多階段檢查閘門的執行有向圖（Execution Graph with Quality Gates）**，確保知識從取得、整理到呈現具備嚴謹的因果相依性與品質校驗。

### 1. 執行流程圖 (Workflow Execution Graph)

```mermaid
flowchart TD
    subgraph S1["階段一：原始文獻 Ingest 與知識沉澱 (Wiki Loop)"]
        R1["搜集 5 篇權威文獻/數據"] --> R2["存入 raw/ (不可變 Source of Truth)"]
        R2 --> R3["萃取核心知識至 wiki/ 各概念頁"]
        R3 --> R4["編織雙向連結 [[wikilink]] 並更新 index.md & log.md"]
        R4 --> QG1{"檢查點 1：知識庫健檢 (Lint)"}
        QG1 -->|發現孤島或死連結| R3
        QG1 -->|通過| S2_IN["進入簡報規劃"]
    end

    subgraph S2["階段二：知識大綱設計 (Outline Graph)"]
        S2_IN --> O1["梳理大學生 4 大痛點與 5 大核心模組"]
        O1 --> O2["產出 9 頁投影片邏輯大綱 (outline.md)"]
        O2 --> QG2{"檢查點 2：受眾痛點與相依檢核"}
        QG2 -->|未通過| O1
        QG2 -->|審查通過 (User 批准)| S3_IN["進入逐頁規格化"]
    end

    subgraph S3["階段三：逐頁腳本與視覺規格化 (Spec Graph)"]
        S3_IN --> SP1["卡片條列化文案 (One Slide, One Idea)"]
        SP1 --> SP2["綁定本地 5 張圖片相對路徑 (./...)"]
        SP2 --> SP3["產出逐頁設計書 (slides-spec.md)"]
        SP3 --> QG3{"檢查點 3：版面可讀性與路徑檢核"}
        QG3 -->|路徑或字數不合規| SP1
        QG3 -->|審查通過 (User 批准)| S4_IN["進入代碼實作"]
    end

    subgraph S4["階段四：HTML 幻燈片組裝與實作 (Deliverable Graph)"]
        S4_IN --> C1["撰寫純 CSS Neo-Brutalism 樣式系統"]
        C1 --> C2["整合圖片與全螢幕 16:9 容器"]
        C2 --> C3["實作原生 JS 鍵盤/按鈕導航邏輯"]
        C3 --> QG4{"檢查點 4：E2E 瀏覽器驗收"}
        QG4 -->|破圖或溢出| C2
        QG4 -->|通過| DELIVER["交付 index.html"]
    end

    subgraph S5["階段五：成果反饋與閉環沉澱 (Closure Loop)"]
        DELIVER --> CL1["簡報結構反向沉澱至 wiki/presentation/"]
        CL1 --> CL2["記錄最終狀態於 log.md"]
    end
```

### 2. 流程機制詳解
1. **哪些步驟會重複執行？（The Loops）**：
   * **Wiki 擴充循環（Ingest Loop）**：每次放入新來源（如這次匯入 5 篇文獻），Agent 就會循環執行「儲存 raw ➔ 萃取至 wiki ➔ 建立雙向連結 ➔ 更新 index/log」。
   * **審查反饋循環（Human-in-the-loop Gate）**：在大綱階段（階段二）與規格階段（階段三），使用者具有一票否決權。若邏輯不順或字數過多，則在規格層重複退回修正，絕不盲目進入寫程式碼階段。
2. **哪些地方需要檢查或重新生成？**：
   * **檢查點 1 (Wiki Lint)**：檢查是否有未連結的孤立頁面、是否有脫離學生現實的昂貴建議。
   * **檢查點 2 (Outline Logic)**：檢查 9 頁之間是否有知識跳躍（例如：必須先講推拉動作與熱身，才能排一週課表）。
   * **檢查點 3 (Asset & Spec Path)**：嚴格檢查引用的本地圖檔路徑是否為精確相對路徑 `./...`，防止產生 404 破圖。
   * **檢查點 4 (E2E Render)**：在瀏覽器中驗證全螢幕切換、鍵盤左右鍵監聽與視窗縮放不破版。
3. **為什麼這樣設計？**：
   * **遵循「先討論、後生成」**：如果直接叫 LLM 一次性產出 500 行的 HTML 簡報，LLM 往往會自行發明不存在的圖片路徑、塞入大段難以閱讀的文字，導致成果無法修改。將流程拆解為「大綱 ➔ 逐頁規格 ➔ HTML 代碼」，能將龐大任務切分為可控的微小節點，大幅降低 Token 浪費與出錯率。

---

## 五、一次實際執行的檢查紀錄 (Verification Records)

| 檢驗階段 | 檢驗項目 | 檢驗方法與指令 | 檢驗結果與狀態 | 處置說明 |
| :--- | :--- | :--- | :--- | :--- |
| **Wiki 健檢** | 5 篇原始資料完整度 | PowerShell 遞迴檢查 `raw/` 目錄數量 | `5 Files Found`（通過） | 涵蓋 ISSN、ACSM、Zone 2、CICO 與超商數據。 |
| **Wiki 健檢** | 概念雙向連結有效性 | 檢閱 `wiki/` 內所有 `[[wikilink]]` 前後參照 | `100% Inbound/Outbound Linked` | 所有核心詞條均收錄於 `index.md`，無孤島頁面。 |
| **大綱檢核** | 受眾痛點覆蓋率 | 比對大學生生活情境（學餐、超商、體育館、考試週） | `Approved by User`（通過） | 獲得使用者回覆「符合」確認。 |
| **規格檢核** | 本地圖片路徑精確性 | 逐一比對 5 張圖檔檔名大小寫與相對路徑 | `Exact Match: ./...`（通過） | 獲得使用者回覆「確認」批准。 |
| **實作驗收** | 圖片檔案實體存在性 | 執行 `Test-Path index.html, *.jpg, *.png` | `True, True, True, True, True, True` | 6 項檔案實體皆存在於同層目錄，無 404 破圖。 |
| **功能驗收** | 鍵盤事件與進度條 | 測試 `ArrowRight`, `ArrowLeft`, `Space`, `F` | `All EventListeners Active` | 換頁流暢、全螢幕功能正常。 |

---

## 六、反思：哪個節點最常出錯？你如何調整檢查流程？

### 1. 哪一個節點最常出錯？
在實際執行中，最容易出錯的節點是**「從概念直接跨越到 HTML 生成時的『版面文字密度過高』與『圖片路徑錯亂』」**。
* **傳統一次性生成常見錯誤**：LLM 往往急於將 Wiki 裡的所有學術細節（如細胞內代謝路徑、1RM 百分比公式）全部一股腦塞進投影片中，導致畫面變成密密麻麻的「Word 貼在網頁上」，嚴重破壞教學簡報的視覺傳達效果；同時容易臆測圖片路徑（例如寫成 `/assets/images/...` 或隨機 Unsplash 網址），導致本地打開一片破圖。

### 2. 發現問題後，把檢查往前移到了哪一個步驟？
我把檢查機制**大幅往前移到了「階段二：逐頁規格化 (slides-spec.md)」**：
* 在正式動筆撰寫任何 HTML / CSS 代碼之前，先在 `slides-spec.md` 中強行規範：
  1. **One Slide, One Idea 原則**：每頁投影片只能有 1 個核心觀念，並強制將文字拆解為 2～3 個 Neo-Brutalism 卡片與標籤貼紙。
  2. **靜態路徑強制錨定**：在規格層直接鎖死本地圖檔路徑為 `./woman-tying-shoelaces-preparing-workout.jpg` 等同層相對路徑，並核對磁碟實體檔名。
  3. **講者口語備忘分離**：將詳細解說抽離至「講者口語備忘（Speaker Notes）」，投影片本體只保留高吸睛度的視覺符號與關鍵字。

### 3. 有沒有因此修改 workflow / graph？為什麼？
**有，我們因此在 Workflow Graph 中增設了兩道「使用者雙重確認閘門 (Quality Gates)」**：
* **修改前原本的直覺流程**：`取得資料 ➔ 寫 Wiki ➔ 直接生成 HTML 簡報`（容易在最後一步發現風格或路徑錯誤而全盤重寫）。
* **修改後健全的 Graph 流程**：
  * `取得資料 ➔ 寫 Wiki ➔ 【閘門 1：大綱確認】➔ 逐頁規格與路徑綁定 ➔ 【閘門 2：規格確認】➔ 生成 HTML ➔ 閉環沉澱`
* **調整原因**：
  * 這種「架構確認 ➔ 視覺規格確認 ➔ 代碼生成」的漸進式 Graph，完全落實了軟體工程的防禦性設計思維。在大綱與文字層發現邏輯不對，修改只需花費幾秒鐘；但若等到寫完 600 行 HTML/CSS 後才發現結構錯誤，重構的代價極高。這套 Graph 設計確保了最終產出的簡報具備極高的一致性、教學性與視覺衝擊力。

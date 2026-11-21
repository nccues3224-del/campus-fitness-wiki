# Wiki 變更與維護日誌 (Changelog)

所有對知識庫的更新、資料匯入（Ingest）、深度查詢沈澱（Query & Compound）及健康檢查（Lint）皆依時間倒序記錄於此。

---

## [2026-11-21] init | 建立大學生健身 LLM Wiki 專案架構
- 依據 Andrej Karpathy LLM Wiki 模式建立核心規範 [[AGENTS.md]]。
- 確立「完全零經驗大學生」受眾定位與四大核心主題：重訓入門、Zone 2 有氧、超商蛋白質、科學減脂。
- 建立三層目錄：`raw/` 來源層、`wiki/` 持久知識庫、根目錄索引與規範。
- 完成美式潮流撞色風格 9 頁全螢幕幻燈片 [[index.html]]、大綱 [[outline.md]] 與逐頁規格 [[slides-spec.md]]。
- 初始化首批 Wiki 基礎概念詞條與索引 [[index.md]]。

## [2026-11-21] ingest | 台灣超商（7-11/全家）高蛋白食品與外食營養標示實測資料庫
- 於 `raw/taiwan-convenience-store-nutrition-db.md` 建立超商平民食物熱量與蛋白質價格比數據庫。
- 更新 [[wiki/nutrition/protein-basics-and-sources.md]]，補全無糖高纖豆漿與茶葉蛋的銅板 CP 值。

## [2026-11-21] ingest | Dr. Kevin Hall (The Lancet) 人體動態能量平衡 CICO 與局部減脂否證研究
- 於 `raw/energy-balance-hall-cico.md` 記錄 CICO 物理守恆與瘦體組織保留模型。
- 更新 [[wiki/concepts/cico-energy-balance.md]] 與 [[wiki/fat-loss/fat-loss-myths.md]]，加入兒茶酚胺脂解機制。

## [2026-11-21] ingest | Dr. San-Millán 粒線體功能與 Zone 2 脂肪氧化研究
- 於 `raw/zone2-fat-oxidation-san-millan.md` 萃取 FatMax 與血乳酸 1.5-2.0 mmol/L 區間。
- 更新 [[wiki/concepts/zone-2-cardio.md]]，補強說話測試法 (Talk Test) 與通氣閥值 VT1 關聯。

## [2026-11-21] ingest | 美國運動醫學會 (ACSM) 初學者阻力訓練指引
- 於 `raw/acsm-exercise-guidelines-resistance.md` 萃取初學者每週 2~3 天全身模式與機械式器材優先原則。
- 更新 [[wiki/training/four-movement-patterns.md]] 與 [[wiki/programming/student-3day-split.md]]。

## [2026-11-21] ingest | 國際運動營養學會 (ISSN) 蛋白質立場聲明
- 於 `raw/issn-protein-exercise-position-stand.md` 存放 ISSN 蛋白質研究核心數據。
- 提煉每日蛋白質 1.2~2.0g/kg 建議，編織更新至 [[wiki/nutrition/protein-basics-and-sources.md]]。

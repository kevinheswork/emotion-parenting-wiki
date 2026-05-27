# 操作紀錄

> Append-only。每次操作追加一筆，不刪改舊紀錄。
> 快速查詢：`grep "^## \[" wiki/log.md | tail -10`

---

## [2026-05-25] init | Wiki 初始化完成

建立目錄結構：`raw/`、`wiki/`、`wiki/concepts/`、`wiki/sessions/`、`wiki/syntheses/`。
建立 CLAUDE.md schema、index.md、log.md、overview.md。

---

## [2026-05-25] ingest | 1-2 孩子為什麼失控？解析情緒暴走的五大原因

新增頁面：
- `wiki/sessions/01-2-孩子為什麼失控五大壓力來源.md`
- `wiki/concepts/五大壓力來源.md`
- `wiki/concepts/Self-Reg vs Self-Discipline.md`
- `wiki/concepts/自我調節.md`
- `wiki/concepts/三層同理心.md`（骨架，待 1-1 ingest 補充）

更新頁面：
- `wiki/overview.md`
- `wiki/index.md`

核心洞見：孩子崩潰是五類壓力超載的訊號；Shanker 以 Self-Reg 替代 Self-Discipline 的框架是本課程基本立場。

---

## [2026-05-25] ingest | 1-3 面對哭鬧不慌

新增頁面：
- `wiki/sessions/01-3-面對哭鬧不慌.md`
- `wiki/concepts/四句口訣.md`
- `wiki/concepts/防災vs救災.md`
- `wiki/concepts/情緒命名.md`

更新頁面：
- `wiki/concepts/自我調節.md`（新增顏色物體冥想技巧）
- `wiki/overview.md`（補充核心論點 4、5，更新概念地圖與課程一覽）
- `wiki/index.md`

核心洞見：情緒教育的核心是防災而非救災；四句口訣（苗頭不對→我猜猜看→原來如此→抱抱他）是本課程第一個可操作的技巧；大人必須先在自己身上練習，才能成為孩子的情緒教練。

---

## [2026-05-25] ingest | 1-4 如何陪伴孩子一步一步認識自己情緒

新增頁面：
- `wiki/sessions/01-4-陪孩子認識自己情緒.md`
- `wiki/concepts/三歲分水嶺.md`
- `wiki/concepts/三個說話術.md`（不逞威風、設定界限、不疾不徐）
- `wiki/concepts/情緒手勢.md`（baby sign 精神）
- `wiki/concepts/三十七十法則.md`
- `wiki/concepts/3C陷阱.md`（密西根大學研究）

更新頁面：
- `wiki/overview.md`（補充核心論點 6、7，擴充概念地圖，新增課程一覽 1-4）
- `wiki/index.md`

核心洞見：四句口訣的應用以三歲為界——三歲前以同理擁抱為主，三歲後才走完完整四步；三個說話術（不逞威風、設定界限、不疾不徐）貫穿所有年齡層；3C 安撫是科學實證的長期危害，短暫特殊情境除外。

---

## [2026-05-25] query | 上網補充 Stuart Shanker 人物資料

新增頁面：
- `wiki/concepts/Stuart-Shanker.md`（學術背景、著作、五領域、Shanker Method 五步驟）

更新頁面：
- `wiki/concepts/自我調節.md`（補充 Shanker Method® 五步驟表格）
- `wiki/index.md`（新增 Stuart-Shanker 條目）

資料來源：self-reg.ca、Wikipedia、ResearchGate。
補充內容：DPhil 學位（數學哲學）、師承 Jerome Bruner、MEHRIT Centre 創辦、四本著作完整資訊、Five Steps（Reframe/Recognize/Reduce/Reflect/Restore）。

---

## [2026-05-25] lint | 健檢完成

### 已修復
- 斷連結：`01-2` 延伸連結中 `[[情緒調節]]` → `[[自我調節]]`（頁面不存在）
- Stuart-Shanker 孤立：補入 `Self-Reg vs Self-Discipline`、`五大壓力來源`、`overview`、`01-2` 的連結
- overview.md frontmatter sources 補入 `1-3 面對哭鬧不慌.md`

### 未修復（待處理）
- **缺口**：`一抱二吻三離開` 在 `防災vs救災` 與 `01-3` 中被引用，無專屬頁面（來源：育兒全百科，待評估是否納入此 wiki）
- 1-1 為序言，不 ingest；`[[三層同理心]]` 骨架頁保留，內容待有實質課程資料時補充

---

## [2026-05-25] ingest | 1-5 面對不要不要期的做法

新增頁面：
- `wiki/sessions/01-5-面對不要不要期的做法.md`
- `wiki/concepts/不要不要期.md`（本質、診斷、肯定句取代疑問句）
- `wiki/concepts/不走心.md`（不把孩子拒絕放心上的心態）
- `wiki/concepts/身體主權.md`（尊重 NO 是長期保護的基礎；爸爸故事）
- `wiki/concepts/七比一原則.md`（正負向語言比例，引自育兒全百科）

更新頁面：
- `wiki/concepts/五大壓力來源.md`（生理壓力補充藥物副作用，含孟魯斯特）
- `wiki/overview.md`（課程一覽補 1-5、演化紀錄）
- `wiki/index.md`（新增四個概念條目）

核心洞見：孩子說不要是自主意識的練習，不是針對父母；「不走心」是情緒穩定的基礎；尊重身體主權在兩歲的練習，是十年後孩子保護自己的心理資本。

### 建議新資料來源
- 1-1 原始逐字稿（補完三層同理心）
- Shanker 原著《Self-Reg》部分章節（英文）可深化五步驟的理解

---

## [2026-05-27] ingest | 2-1 真的不能打嗎？

新增頁面：
- `wiki/sessions/02-1-真的不能打嗎.md`
- `wiki/concepts/體罰.md`（Lancet 2021 統合分析、6歲以下風險、AAP聲明、常見誤解破解）
- `wiki/concepts/威嚇式教養.md`（五大副作用：成效短暫/惡性循環/培養說謊/反社會/暴力即權力）
- `wiki/concepts/內在動機.md`（威嚇教養的根本犧牲品）

更新頁面：
- `wiki/overview.md`（補充核心論點 8、課程一覽 2-1、演化紀錄）
- `wiki/index.md`（新增三個概念條目與 session 條目）

核心洞見：課程從「理解情緒」進入「管教行為」；體罰與威嚇式教養皆有嚴重科學實證的副作用，選擇體罰是最偷懶的教養方式；說服式管教的長期成功率是威嚇的兩倍；下一課將提供科學有效的替代方法。

---

## [2026-05-27] ingest | 2-2 不發脾氣也能教

新增頁面：
- `wiki/sessions/02-2-不發脾氣也能教.md`
- `wiki/concepts/六種領導風格.md`（Daniel Goleman 六型領導：願景/教練/關係/民主/進度/命令）
- `wiki/concepts/LATER口訣.md`（Leave/Ask/Time Out/Embrace/Review 完整說明）

更新頁面：
- `wiki/concepts/三十七十法則.md`（補充「如何選擇 30%」：八二法則應用、六種領導風格連結）
- `wiki/overview.md`（補充核心論點 9、課程一覽 2-2、演化紀錄）
- `wiki/index.md`（新增兩個概念條目與 session 條目）

核心洞見：本課提供 2-1 批判之後的「正面替代方案」，完整流程是：四句口訣（同理）→ 六種領導風格（設計對策）→ LATER 口訣（罰則執行）。關鍵澄清：「溫柔而堅定」不是冷暴力（面無表情要孩子照做），而是這整套情緒同理 + 領導風格的細節縮寫。懲罰原則：必須與行為相關，才能喚醒大腦警鈴。

---

## [2026-05-27] ingest | 2-3 不小心罵了孩子？怎麼樣才能補救？

新增頁面：
- `wiki/sessions/02-3-不小心罵了孩子怎麼補救.md`
- `wiki/concepts/道歉五步驟.md`（Gary Chapman 五步驟：表達悔意/承擔責任/願意補償/真實改變/請求原諒）

更新頁面：
- `wiki/concepts/四句口訣.md`（新增「用在自己身上」段落：父母爆發後先自我探索，再補救）
- `wiki/overview.md`（補充核心論點 10、課程一覽 2-3、演化紀錄）
- `wiki/index.md`（新增一個概念條目與 session 條目）

核心洞見：四句口訣是通用情緒探索框架，不只用在孩子，也可用在父母自己身上——爆發後先從五大需求猜自己的原因、命名情緒（不只是「生氣」，可能是疲倦/羞愧/挫折）、然後去找能充電的人。補救的核心是「真實改變」而非反覆道歉循環；青少年真實案例說明每天寫紙條的具體行動比言語道歉更有效。

---

## [2026-05-27] ingest | 2-4 當另一半對孩子發火的時候，我該怎麼辦

新增頁面：
- `wiki/sessions/02-4-教養不同調怎麼辦.md`
- `wiki/concepts/教養不同調.md`（三層應對框架：當下/事後/暫時共識 + 為孩子設安全網）
- `wiki/concepts/三明治說話術.md`（先肯定善意動機再開啟真正對話）

更新頁面：
- `wiki/concepts/四句口訣.md`（新增「用在伴侶身上」段落，完整三層應用：孩子→自己→伴侶）
- `wiki/overview.md`（補充核心論點 11、課程一覽 2-4、演化紀錄）
- `wiki/index.md`（新增兩個概念條目與 session 條目）

核心洞見：四句口訣的應用對象擴展到第三層（伴侶），完整三層：孩子（防災）→ 自己（爆發後自癒）→ 伴侶（教養不同調時的情緒引導）。教養不同調不要在當下正面衝突，而是事後用三明治說話術打開對話空間；溝通無效時設暫時共識（各自負責），同步替孩子接住情緒並翻譯另一半的善意。黃醫師自我披露：自己三歲前也是虎爸，改變的契機是「開門看到孩子臉色垮下來」那個畫面——說明改變需要自己的時機，不是被強迫的。

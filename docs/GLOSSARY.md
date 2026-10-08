> 專案：智能快遞櫃系統  
> 維護：R9 文件與品質  
> 更新日期：2026-10-8

## 一、Scrum 與專案管理

| 中文 | English | 說明 |
| --- | --- | --- |
| 敏捷開發 | Agile Development | 以迭代、增量方式交付軟體的開發方法。 |
| Scrum | Scrum | 一種敏捷開發框架，以 Sprint 為單位迭代。 |
| Sprint | Sprint | 固定長度的迭代週期。 |
| 產品負責人 | Product Owner (PO) | 負責產品待辦列表與需求優先級的人。 |
| Scrum Master | Scrum Master | 負責移除障礙、促進 Scrum 流程的人。 |
| 產品待辦列表 | Product Backlog | 依優先級排序的需求列表。 |
| Sprint 待辦列表 | Sprint Backlog | 當前 Sprint 要完成的任務列表。 |
| 驗收標準 | Acceptance Criteria | 判斷需求是否完成的可驗證條件。 |
| 完成定義 | Definition of Done (DoD) | 團隊共同約定的「完成」標準。 |
| 里程碑 | Milestone | 專案中的重要檢查點。 |
| 風險登記冊 | Risk Register | 記錄風險、可能性、影響與應對措施。 |
| 變更日誌 | Change Log | 記錄需求、設計或範圍變更。 |
| 回顧會議 | Retrospective | Sprint 結束後檢討改進的會議。 |
| 每日站會 | Daily Stand-up | 每日簡短同步進度的會議。 |
| 速度 | Velocity | 團隊每個 Sprint 完成的任務量。 |
| 燃盡圖 | Burndown Chart | 顯示剩餘工作量隨時間變化的圖。 |
| 甘特圖 | Gantt Chart | 顯示任務排程與時間關係的圖。 |
| 進度評審 | Progress Review | 課堂上的階段性成果評審。 |
| 個人日誌 | Logbook | 每位成員的每週工作與證據記錄。 |
| 貢獻熱力圖 | Contribution Heatmap | GitHub 上的貢獻活動視覺化。 |

## 二、需求與設計

| 中文 | English | 說明 |
| --- | --- | --- |
| 需求規格說明書 | Software Requirements Specification (SRS) | 完整描述系統需求的文件。 |
| 功能需求 | Functional Requirement (FR) | 系統必須提供的功能。 |
| 非功能需求 | Non-Functional Requirement (NFR) | 效能、安全、可用性等品質要求。 |
| 需求追蹤矩陣 | Requirements Traceability Matrix (RTM / RIM) | 需求到設計、程式、測試的對應表。 |
| 使用者故事 | User Story | 從使用者角度描述需求的短句。 |
| 使用者畫像 | Persona | 代表目標使用者的虛構人物。 |
| 使用者旅程圖 | Journey Map | 使用者在系統中完成目標的流程圖。 |
| 用例圖 | Use Case Diagram | UML 圖，描述角色與系統功能關係。 |
| 時序圖 | Sequence Diagram | UML 圖，描述物件間互動順序。 |
| 類別圖 | Class Diagram | UML 圖，描述類別、屬性與關係。 |
| 活動圖 | Activity Diagram | UML 圖，描述流程與分支。 |
| 狀態機圖 | State Machine Diagram | UML 圖，描述狀態轉移。 |
| 實體關係圖 | Entity-Relationship Diagram (ERD) | 資料庫表與關係設計圖。 |
| 架構決策記錄 | Architecture Decision Record (ADR) | 記錄重要架構決策與理由。 |
| 介面契約 | API Contract | 前後端約定的 API 規格。 |
| OpenAPI | OpenAPI Specification | 描述 REST API 的標準格式。 |
| 統一建模語言 | Unified Modeling Language (UML) | 軟體建模的標準圖形語言。 |
| 設計系統 | Design System | 色彩、字體、間距、元件規範。 |
| 風格指南 | Style Guide | 視覺與元件使用規範。 |
| 高保真原型 | High-Fidelity Prototype | 接近最終視覺的可點擊原型。 |
| 可用性評審 | Usability Review | 檢查介面是否易用的評審。 |
| 啟發式評估 | Heuristic Evaluation | 依 Nielsen 十原則檢查可用性。 |

## 三、開發與運維

| 中文 | English | 說明 |
| --- | --- | --- |
| 持續整合 | Continuous Integration (CI) | 每次提交自動建置與測試。 |
| 持續部署 | Continuous Deployment (CD) | 自動部署到環境。 |
| 容器化 | Containerization | 用 Docker 封裝應用與環境。 |
| 資料庫遷移 | Database Migration | 版本化變更資料庫結構。 |
| 種子資料 | Seed Data | 初始化測試資料。 |
| 身分認證 | Authentication | 確認使用者身分。 |
| 授權 | Authorization | 確認使用者權限。 |
| 角色型存取控制 | Role-Based Access Control (RBAC) | 依角色分配權限。 |
| JSON Web Token | JWT | 常用於登入驗證的 Token。 |
| 審計日誌 | Audit Log | 記錄誰在何時對什麼資源做了什麼。 |
| 冪等 | Idempotency | 重複執行結果一致。 |
| 併發安全 | Concurrency Safety | 多請求下避免資料錯誤。 |
| 原子分配 | Atomic Allocation | 分配格口時不可被中斷或重複。 |
| 唯一索引 | Unique Index | 資料庫層防止重複。 |
| 心跳上報 | Heartbeat Reporting | 櫃機定期回報狀態。 |
| 開箱指令 | Unlock Command | 控制櫃門開啟的指令。 |
| 站內信 | In-App Notification | 系統內的通知訊息。 |
| 即時推送 | Real-Time Push | 透過 Socket.IO 等方式即時更新。 |
| 定時任務 | Scheduled Task / Cron Job | 定期執行的任務。 |
| 模擬服務 | Mock Service / Fake Service | 模擬外部系統的測試服務。 |

## 四、業務領域

| 中文 | English | 說明 |
| --- | --- | --- |
| 櫃機 | Smart Locker | 智能快遞櫃設備。 |
| 格口 | Locker Cell / Compartment | 櫃機中的單一儲物格。 |
| 取件碼 | Pickup Code | 取件用的驗證碼。 |
| 代取授權 | Pickup Authorization | 授權他人代取包裹。 |
| 異常件工單 | Exception Ticket | 滯留、超期、破損、丟件等工單。 |
| 計費引擎 | Billing Engine | 計算尺寸、時長、超期費用。 |
| 核銷 | Redemption / Verification | 驗證並完成取件。 |
| 對帳單 | Statement | 快遞員月度費用報表。 |
| 週轉率 | Turnover Rate | 格口使用效率指標。 |

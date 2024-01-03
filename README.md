# 軟件工程火車票售票系統概要
# 火車售票系統
## 1.引言
隨著計算機技術的發展，用計算機位人們的生活服務已經變的普及化。鐵路公司為了增強公司的信息化程度，提高公司的售票管理的效率，就建立起了相應的火車訂票系統，實現提高了火車克用系統的售票效率和管理水平。
火車票訂票系統是典型的信息管理系統的一部分，火車票訂票系統的開發充分利用了計算機信息技術提高了火車票訂票的管理水平、服務水平。系統實現了乘客查詢信息、訂票操作、銷售統計等功能，可明顯對火車票訂票的有效管理。
### 編寫目的
本火車站售票系統的根本目的在於通過計算機實現票務信息的統一管理，來提高工作效率，使售票員售票和乘客購票更加方便。實現計算機管理的最佳技術就是數據庫技術。我們可以利用數據庫將整個火車站的票務情況存入計算機，在配置上功能豐富的用戶接口，以滿足用戶需求。一個火車站售票信息管理系統應達到的目標是提供及時、準確的信息服務，加快信息探逤的效率，實況靈活的查詢，減輕管理人員製作報表和統計分析的負擔，且系統規模不太大，但又要保證支持日常工作的要求，以便系統應易於擴充，方便日後統一聯網與管理，提高管理水平。
### 範圍
軟件系統名稱:火車票預定系統
該系統的中心功能是列車車次和售票信息的查詢功能和售票功能。雖然兩個看似截然不同的功能但他們在實現上十分的類似，售票就需要首先先通過查詢的方式得到滿足要求的列車車次，然後再根據實際情況進行售票。所以售票功能可以看成是列車車次和售票信息查詢功能的延伸。
支出:該系統是軟件工程作業，故無經費支出。
收益:系統完成後即刻交付使用，主要是為了方便火車站售票人員使用，有重大的利益。

## 2.項目概述
### 產品描述
火車票售票系統是一個融合火車票的訂票、賣票、退票、車票管理、售票點管理、列車車信息查詢查詢及售票信息查詢等為融為一身的綜合系統。
### 產品功能
本系統主要用於火車票的銷售，提供了以下幾個子功能:用戶註冊登入和火車信息查詢、訂票查詢、火車票預訂、退票申請以及後台方面的列車車次信息發布更新、車票生成、提供取票服務成等後臺功能。
根據可行性研究的結果和客戶的要求，分析現有情況及問題，採用Client/Server結構，將火車票售票系統劃分為兩個子系統:客戶端子系統，服務器端子系統。故火車票售票系統將由四部分組成:網上訂票客戶端系統，售票員服務系統，系統管理員系統、數據庫服務器管理系統。本系統的各個系統的關係如下:![](https://github.com/0senyu0/final-report/blob/main/%E7%81%AB%E8%BB%8A%E7%B3%BB%E7%B5%B1%E9%97%9C%E4%BF%82%E5%9C%96.drawio.svg)
系統數據流程圖:

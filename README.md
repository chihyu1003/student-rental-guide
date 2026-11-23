# 📄 raw/ 原始資料存證目錄說明手冊 (Primary Source Ledger)

> 本目錄存放「大學生租屋指南」LLM Wiki 之五份官方真實資料文字存證。
> 本目錄為 **只讀層（Immutable Truth Source）**，所有內容均忠實引述官方正式法規、政府公告與權威機構檢核表，絕無人工改寫、教學摘要或虛構條文。

---

## 📋 五份官方原始資料存證清單與擷取狀態

| 編號 | 存證檔案名稱 | 正式文件名稱 | 主管／發布機關 | 發布／修正日期 | 官方來源網址 | 檔案格式 | 擷取狀態與檢核結論 |
| :---: | :--- | :--- | :--- | :--- | :--- | :---: | :---: |
| **01** | `01_moi_rental_contract_provisions.txt` | 《住宅租賃定型化契約應記載及不得記載事項》 | 中華民國內政部 | 114 年 4 月 18 日公告修正應記載事項第 18 點 | [內政部主管法規系統](https://law.moi.gov.tw/LawContent.aspx?id=GL000407) | TXT | **完整存證**<br>含應記載事項 22 點及不得記載事項 10 點全文 |
| **02** | `02_taipower_electricity_regulations.txt` | 內政部電費新制公告（台內地字第 1130263933 號）及台灣電力公司〈承租人申請住宅租屋電費查詢作業要點〉 | 內政部、台灣電力股份有限公司 | 113 年 7 月 8 日公告，113 年 7 月 15 日生效 | [行政院公報資訊網](https://gazette.nat.gov.tw/egFront/detail.do?metaid=150616)<br>[台電網路櫃檯](https://service.taipower.com.tw/ebpps2/web/index?funName=1004) | TXT | **完整存證**<br>含第 6 點及第 11 點修正條文與台電要點全文 |
| **03** | `03_nlma_rent_subsidy_regulations.txt` | 《三百億元中央擴大租金補貼專案計畫 115 年度受理申請公告》及作業規定 | 內政部國土管理署 | 受理期間 115.01.01-115.12.31，作業規定 115.10.06 修正 | [不動產資訊平台專區](https://pip.moi.gov.tw/V3/B/SCRB0102.aspx)<br>[國土署線上申請系統](https://has.nlma.gov.tw/subsidyOnline/house300e/) | TXT | **完整存證**<br>含家庭成員、所得 3 倍、持分合計 40㎡、加碼與過渡條款 |
| **04** | `04_rental_disputes_and_cpc_procedures.txt` | 《租賃住宅市場發展及管理條例》（第 4、5、7、8、11、16 條）、《民法》（第 432 條）及《消費者保護法》（第 43、44 條） | 中華民國內政部、法務部、行政院消保會 | 租賃條例 112.02.08 總統令公布，定型化契約 114.04.18 最新修正 | [全國法規資料庫 (租賃條例)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=D0060125)<br>[消保會線上申訴](https://appeal.cpc.ey.gov.tw) | TXT | **完整存證**<br>含專法第 4 條例外、第 5 條消保關係、修繕第 9 點、任意終止第 14 點及雙軌救濟 |
| **05** | `05_fire_safety_alarm_and_water_heater.txt` | 《住宅用火災警報器設置辦法》、《燃氣熱水器及其配管安裝標準》、《消防法》及《公寓大廈管理條例》 | 中華民國內政部、內政部消防署 | 住警器辦法 99.12.30 發布，熱水器標準 109.11.10 修正（第 6 條已刪除） | [全國法規資料庫 (熱水器標準)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=D0120013)<br>[全國法規資料庫 (住警器辦法)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=D0120046)<br>[消防署下載專區](https://www.nfa.gov.tw) | TXT | **完整存證**<br>含住警器第 3 至 8 條、熱水器第 3 至 9 條、公寓大廈通道規定與官方安全診斷表項目 |

---

## 🔍 原始資料驗證與編碼標準
- **檔案編碼**：全部採用標準 **UTF-8（無 BOM）**，確保跨平台（Windows, Linux, macOS）與各類 LLM Agent / Python 處理腳本讀取無亂碼。
- **純文字存證性**：排除了網頁動態腳本與多餘排版標籤，保留法規與官方公告最純淨、最真實之條文依據。

# 2022.Software.Developer-II
請依照下面虛擬情境的需求以及要求之技術，完成該情境需求的系統

**今天我們需要提供一個資料平台給用戶端的系統呼叫，可以讀取EXCEL內的Sheet資料，將其資料儲存到資料庫，每次讀取Excel File時候，要將原資料刪除，除了將資料寫入資料庫外，也同時必須讓資料可以讀出**

##### 原始需求
1. 建立一個Console Application 將Excel內容共有兩個Sheet，儲存到資料表
2. Console Application必須透過Web API將資料儲存
3. Console Application必須透過Web API將資料取出

# Skill Requirement
> 環境
- 請將開發之系統，佈署至Micrsoft Azure (可免費使用30天)
- 請將程式碼透過Azure DevOps Service進行版控 (可免費使用)，請將專案設定公開
> 技術
- Console : 請使用NET Core 6 開發
- Web API : 請使用.Net6開發
- DataBase : 請使用MS SQL開發SQL程式，務必使用SQL Project做版控，一律採用Store procedure開發
- Pipeline : 請使用Azure Devops Service的 CI/CD 自動佈署Web API
- 請使用Drapper

> 請用Signalr技術完成即時通訊的需求，所有開發都必須有版控機制

# Acceptance Criteria
> 時間
- 依照HR指定時間完成，並再跟HR約第二次面談時間

> 成果展示
- 於第二次面試時間的前一週，分享自己在Azure DevOps Service的`Repository`給主考官，Repository須設定為公開

> 第二次面試時，請現場Demo作品及說明系統架構
- Demo時
  1. Web API / Azure SQL database放置雲端
  2. Console 程式呼叫API取得資料
  3. 能PostMan呼叫API取出資料

> 請依照`Description`，發揮創意、設計解決方案

> 第二次面試時，請闡述你所認知`DevOps` 

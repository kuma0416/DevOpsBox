# DevOpsBox: 用 C++ 打造的分散式 DevOps 系統

## 📌 專案簡介

DevOpsBox 是一個學習型專案，目標是以 **C++** 開發微服務，結合 **gRPC** 通訊、**Kafka** 事件流，並以 **Python (Django/FastAPI)** 製作前端管理介面，實現一個完整的 DevOps 工具平台。  
本專案適合想學習 **分散式系統架構**、**事件流設計**、**微服務實作**，以及 **C++ 應用於現代軟體開發** 的工程師。

## 🌐 系統架構

![](architecture.png)  
（見 `architecture.md`）

## 🧱 技術棧

| 模組            | 技術                       |
|-----------------|---------------------------|
| 微服務          | C++ + gRPC                 |
| 事件流          | Kafka                      |
| 前端 UI         | Django 或 FastAPI + Jinja2 |
| API Gateway     | FastAPI (Python)           |
| 資料庫          | PostgreSQL / MongoDB       |
| 容器化與部署    | Docker + docker-compose    |

## 📦 功能模組

- **Git Service**: 代碼版本管理 (clone/pull)
- **Build Service**: 編譯構建管理 (Makefile)
- **Deploy Service**: 自動部署 (SSH)
- **Log Service**: 日誌收集與查詢
- **Monitor Service**: 系統資源監控 (CPU/Mem/Disk)
- **Kafka Bus**: 微服務間事件流傳遞
- **API Gateway**: 前後端 API 橋樑
- **Web 前端**: 顯示流程狀態、日誌與監控

## 🏁 進度規劃

| 週次 | 任務                             |
|------|----------------------------------|
| 1    | 專案啟動 & 架構設計 (本週)       |
| 2    | 設計 gRPC proto 檔                |
| 3    | 搭建 C++ gRPC 環境               |
| ...  | ...                              |
| 16   | 系統整合測試 & Demo 完成         |

## 📝 授權

MIT License

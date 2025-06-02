# Tools Checklist: DevOpsBox 專案工具清單

以下是專案開發需要安裝與設定的工具列表，請依照順序確認安裝完成。

---

## 🖥️ 系統環境

✅ 建議作業系統：
- Linux (Ubuntu 22.04 LTS)
- 或 Windows WSL2 + Ubuntu

✅ 必備套件：
- GCC / Clang / MSVC (C++ 編譯器)
- CMake >= 3.20
- Git >= 2.40
- Python >= 3.10 (推薦 venv 虛擬環境)

---

## 🔧 開發工具

| 工具/套件          | 版本建議       | 安裝方式/說明                                   |
|--------------------|---------------|-----------------------------------------------|
| gRPC (C++ SDK)     | >= 1.56.0     | [gRPC 官方教學](https://grpc.io/docs/languages/cpp/quickstart/) |
| Protobuf Compiler   | >= 21.0       | `apt install protobuf-compiler` 或手動編譯     |
| Kafka              | >= 3.x        | [Apache Kafka 官方下載](https://kafka.apache.org/downloads) |
| Kafka C++ Client (cppkafka) | 最新穩定版 | https://github.com/mfontanini/cppkafka        |
| Docker             | >= 24.0       | [Docker 官方安裝教學](https://docs.docker.com/get-docker/) |
| Docker Compose     | >= 2.0        | 已內建於 Docker                               |
| Django (或 FastAPI) | Django >= 4.0 / FastAPI >= 0.100 | `pip install django` / `pip install fastapi`   |
| PostgreSQL (選用)   | >= 15.x       | `apt install postgresql` 或 Docker 安裝         |
| Mermaid 繪圖工具   | N/A           | VSCode Plugin, Obsidian, Typora, 或網頁版 [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) |

---

## 📂 環境配置檔案（後續補充）

- `CMakeLists.txt` (gRPC C++ 編譯)
- `docker-compose.yml` (多服務容器啟動)
- `.env` (環境變數設定檔)

---

✅ **安裝進度確認表**

| 工具/套件          | 安裝狀態 (✅ / ❌) | 備註                     |
|--------------------|------------------|--------------------------|
| gRPC (C++)         | ❌               |                           |
| Protobuf Compiler   | ❌               |                           |
| Kafka              | ❌               |                           |
| Kafka C++ Client    | ❌               |                           |
| Docker             | ❌               |                           |
| Django/FastAPI      | ❌               |                           |
| PostgreSQL          | ❌               | 選用，可先不裝            |
| Mermaid 繪圖工具    | ❌               | 線上版也可使用             |

---

## 📌 注意事項

- 建議建立虛擬環境（Python venv / Conda）
- C++ 編譯工具鏈與 CMake 配合使用
- Kafka 安裝可考慮 Docker 版，方便開發
- 日後會提供 `CMakeLists.txt` / `docker-compose.yml` 範例


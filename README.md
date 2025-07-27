
# 🚀 BlockPulse Crypto Data Warehouse Project

This repository contains the full data engineering pipeline and dimensional data warehouse implementation for **BlockPulse Insights**, a cloud-based cryptocurrency analytics startup.

Built as a capstone project, this solution ingests, processes, and models real-time crypto market data into a structured, queryable data warehouse, supporting advanced trend analysis and dashboarding.


## 📌 Project Overview

- **Data Source**: [CoinGecko Public API](https://www.coingecko.com/en/api)
- **Pipeline**: Ingests and processes daily market snapshots (price, volume, market cap, etc.)
- **Storage**: Azure Data Lake Gen2 with Delta Lake format (bronze, silver, gold layers)
- **Data Warehouse**: Star schema model with fact/dimension tables
- **Analytics Tools**: Azure Synapse Analytics, Power BI, or Databricks SQL

---

## 🧱 Architecture

<img width="1581" height="612" alt="image" src="https://github.com/user-attachments/assets/e241d047-d363-466c-b03f-1f7a41274079" />

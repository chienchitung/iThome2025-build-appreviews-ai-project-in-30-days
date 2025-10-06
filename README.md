# iThome 2025 鐵人賽 - 30 天打造 App 評論洞察系統：用 AI 讓產品團隊更懂用戶

## 應用程式評論 AI 洞察系統 (App Reviews AI Insights System)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🚀 專案簡介 (Project Overview)

這是一個從實際工作痛點出發，完整開發的 **MVP (Minimum Viable Product) 版本的 AI 系統**。它的核心目標是自動化且智慧化地分析來自 **App Store / Google Play** 的海量使用者評論，快速提煉出產品或服務的**關鍵顧客痛點與趨勢**。

本專案結合了**資料爬取、清理、AI 模型訓練（基於 BERT）**，以及最終的 **Dashboard 系統開發與部署**。旨在將產品與客服團隊從耗時的**人工評論整理與分類**工作中解放出來，轉而專注於更有價值的產品迭代與決策。

這個系統證明了將**非結構化的評論資料**轉化為**即時、可操作的商業洞察**的巨大潛力。

---

## ✨ 核心特色與價值 (Key Features & Value)

* **全自動化流程：** 實現從應用程式商店爬取評論資料到數據分析儀表板的**端到端**自動化。
* **AI 驅動的洞察：** 利用 **BERT 語言模型**對評論進行精準的**主題分類與情緒分析**，超越傳統的關鍵字統計。
* **節省人力成本：** 大幅降低過去耗費在人工標註、整理與建立儀表板上的人力與時間。
* **即時掌握痛點：** 幫助產品經理與客服團隊**即時、快速**掌握顧客的最新回饋、痛點與建議，加速決策。

---

## 📚 完整開發歷程：iThome 鐵人賽 30 篇文章

這個專案的完整開發過程——從**環境建置、爬蟲設計、資料清洗、BERT 模型訓練，到系統部署**——所有環節的決策與實作細節，都記錄在以下 **30 篇**文章中。

| 日期 | 文章標題 | 連結 |
| :---: | :--- | :--- |
| Day 0 | **前言** | [連結](https://ithelp.ithome.com.tw/articles/10375301) |
| Day 1 | 專案規劃準備 | [連結](https://ithelp.ithome.com.tw/articles/10375338) |
| Day 2 | 工具與環境設置 | [連結](https://ithelp.ithome.com.tw/articles/10375342) |
| **資料爬取與整理 (Day 3-11)** | **App Store / Google Play 評論爬蟲設計與資料前處理** | |
| Day 3 | 如何從 App Store / Google Play 爬取應用程式評論資料 | [連結](https://ithelp.ithome.com.tw/articles/10375480) |
| Day 4 | App 評論爬蟲設計與實作（1/5） | [連結](https://ithelp.ithome.com.tw/articles/10375624) |
| Day 5 | App 評論爬蟲設計與實作（2/5） | [連結](https://ithelp.ithome.com.tw/articles/10375955) |
| Day 6 | App 評論爬蟲設計與實作（3/5） | [連結](https://ithelp.ithome.com.tw/articles/10376155) |
| Day 7 | App 評論爬蟲設計與實作（4/5） | [連結](https://ithelp.ithome.com.tw/articles/10376354) |
| Day 8 | App 評論爬蟲設計與實作（5/5） | [連結](https://ithelp.ithome.com.tw/articles/10376464) |
| Day 9 | 原始資料格式解析與初步檢查 | [連結](https://ithelp.ithome.com.tw/articles/10376571) |
| Day 10 | 資料前處理 | [連結](https://ithelp.ithome.com.tw/articles/10376765) |
| Day 11 | 資料探索性分析與視覺化 | [連結](https://ithelp.ithome.com.tw/articles/10376971) |
| **AI 資料標註與模型訓練 (Day 12-22)** | **從標註規則、LLM 加速標註到 BERT 模型訓練與部署** | |
| Day 12 | 資料標註規則與主題分類定義 | [連結](https://ithelp.ithome.com.tw/articles/10377153) |
| Day 13 | 資料標註：工具選擇與實作流程 | [連結](https://ithelp.ithome.com.tw/articles/10377388) |
| Day 14 | 標註品質控管與一致性檢查：為什麼資料標註不能馬虎？ | [連結](https://ithelp.ithome.com.tw/articles/10377556) |
| Day 15 | 利用大型語言模型（LLM）加速資料標註流程 | [連結](https://ithelp.ithome.com.tw/articles/10377746) |
| Day 16 | 訓練語言模型的選擇：為什麼我用 BERT？ | [連結](https://ithelp.ithome.com.tw/articles/10377841) |
| Day 17 | 使用 LLM 進行自動標註流程 | [連結](https://ithelp.ithome.com.tw/articles/10377983) |
| Day 18 | BERT 模型訓練實作流程 | [連結](https://ithelp.ithome.com.tw/articles/10378387) |
| Day 19 | 評估指標介紹與選擇 | [連結](https://ithelp.ithome.com.tw/articles/10378522) |
| Day 20 | 提升模型性能：超參數調校與優化 | [連結](https://ithelp.ithome.com.tw/articles/10378816) |
| Day 21 | Hugging Face：不只是模型庫，更是 AI 開發生態系 | [連結](https://ithelp.ithome.com.tw/articles/10379064) |
| Day 22 | 模型上傳流程與部署後測試 | [連結](https://ithelp.ithome.com.tw/articles/10379425) |
| **系統開發與部署 (Day 23-29)** | **從 Dashboard 設計到最終系統上線** | |
| Day 23 | Dashboard 初版設計與系統開發設計 | [連結](https://ithelp.ithome.com.tw/articles/10379433) |
| Day 24 | 系統開發設計與實作（1/4） | [連結](https://ithelp.ithome.com.tw/articles/10380394) |
| Day 25 | 系統開發設計與實作（2/4） | [連結](https://ithelp.ithome.com.tw/articles/10382701) |
| Day 26 | 系統開發設計與實作（3/4） | [連結](https://ithelp.ithome.com.tw/articles/10382703) |
| Day 27 | 系統開發設計與實作（4/4） | [連結](https://ithelp.ithome.com.tw/articles/10382708) |
| Day 28 | 系統使用者測試 | [連結](https://ithelp.ithome.com.tw/articles/10382711) |
| Day 29 | 系統部署上線 | [連結](https://ithelp.ithome.com.tw/articles/10382718) |

---

## 🤝 貢獻與交流 (Contribution & Discussion)

非常感謝您完整閱讀這系列文章並親手實踐這個 AI 評論洞察系統！

儘管開發過程充滿挑戰，尤其在後半段遭遇些許波折，但仍完成這項不可能的任務！

如果您有任何關於**功能優化、程式碼重構、模型效能提升**，或是**實務應用**上的寶貴建議，都**非常歡迎透過 GitHub Issue 或 Pull Request 提出**！您的回饋將幫助這個系統更臻完善。

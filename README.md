# 🥗 AI 營養導航系統

> 基於 N8N 工作流程自動化的智能營養推薦平台

[![N8N](https://img.shields.io/badge/N8N-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io/)
[![LINE Bot](https://img.shields.io/badge/LINE-00C300?style=for-the-badge&logo=line&logoColor=white)](https://line.me/)
[![Groq AI](https://img.shields.io/badge/Groq-000000?style=for-the-badge)](https://groq.com/)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)

## 📺 Project Demo Video
[![AI Nutrition Navigator Demo](https://img.youtube.com/vi/Qv3KjP5daQk/0.jpg)](https://youtu.be/Qv3KjP5daQk)
*Click the image above to watch the full system demonstration on YouTube.*

## 🎯 專案簡介

AI 營養導航系統是基於 N8N 工作流程引擎開發的智能營養推薦平台，整合 LINE Bot、Google Maps API、Groq AI 與 Supabase 資料庫，為使用者提供個人化的餐廳推薦與營養建議。

### 🌟 核心價值
- ✅ 工作流程自動化：50+ N8N 節點
- ✅ AI 深度分析：Groq Llama 3.3 70B
- ✅ 多源資料整合：Google Maps + LINE + Supabase
- ✅ 個人化推薦：9 個維度用戶畫像

## ✨ 核心功能

### 🔄 智能工作流程
- 🆕 新用戶註冊（9 步驟資料收集）
- 👤 老用戶識別（自動確認位置）
- 🔍 即時搜尋（2km 範圍餐廳）
- 📜 歷史查詢（過去 5 筆記錄）

### 🍽️ 菜系分類
支援 6 大菜系智能分類：
- 🥢 中式料理
- 🍣 日式料理
- 🍲 火鍋
- 🥗 健康餐
- 🌍 異國料理
- ☕ 咖啡廳

### 🤖 AI 營養分析
- 📊 BMR 計算與熱量目標
- 🏆 5 家餐廳 CP 值對比
- 🍽️ 具體點餐建議
- ❌ 避雷指南
- 💡 專業營養撇步

## 🛠️ 技術架構

### 核心技術棧
- **自動化引擎**: N8N (50+ 節點)
- **AI 模型**: Groq Llama 3.3 70B
- **通訊平台**: LINE Messaging API
- **地圖服務**: Google Maps API
- **資料庫**: Supabase (PostgreSQL)

### 系統流程
LINE 用戶 → Webhook → N8N 工作流程 → Google Maps/Groq AI → Supabase → LINE 回覆

Code

## 📸 系統截圖

> 展示 N8N 工作流程、LINE 介面、AI 分析結果

## 🔄 工作流程檔案

N8N 工作流程位於 `workflows/main-workflow.json`

### 匯入步驟
1. 安裝 N8N: `npm install -g n8n`
2. 啟動: `n8n start`
3. 匯入 JSON 檔案
4. 設定 API 憑證

## 🗄️ 資料庫結構

### users_profile
- 用戶基本資料（9 個欄位）
- setup_step 追蹤設定進度

### nutrition_recommendations
- 推薦主記錄
- 外鍵關聯用戶

### recommended_restaurants
- 餐廳詳細分析
- 外鍵關聯推薦記錄

## 📊 專案成果

| 指標 | 數據 |
|------|------|
| 🔄 工作流程節點 | 50+ 個 |
| 🌐 API 整合 | 4 個 |
| 🗄️ 資料庫表格 | 3 個 |
| 🍽️ 菜系分類 | 6 大菜系 |
| ⚡ 開發時間 | 3 週 |

## 🎯 技術亮點

1. **複雜工作流程設計**
   - 50+ 節點的大型工作流程
   - 狀態機設計（9 步驟）

2. **AI 整合應用**
   - Groq AI 菜系分類
   - Structured Output Parser

3. **API 串接能力**
   - LINE + Google Maps + Supabase
   - Webhook 與 Push/Reply 訊息

## 🎥 展示資源

- 📊 專案簡報 (PPT)
- 🎥 展示影片
- 📸 系統截圖
- 📚 N8N 工作流程 JSON

## 🚀 快速開始

### 使用 N8N Desktop
1. 下載 [N8N Desktop](https://n8n.io/download)
2. 匯入工作流程 JSON
3. 設定 API 憑證
4. 啟用工作流程

## 🚧 未來規劃

- [ ] 多日行程規劃
- [ ] 推薦準確率追蹤
- [ ] 社群分享功能
- [ ] LINE Rich Menu

## 📝 授權

MIT License

## 👤 作者

**tsoAI0305**

- GitHub: [@tsoAI0305](https://github.com/tsoAI0305)
- Portfolio: [查看作品集](https://github.com/tsoAI0305/portfolio)

## 🙏 致謝

- N8N - 工作流程自動化平台
- Groq - AI 推理引擎
- LINE - 通訊平台
- Google Maps - 地圖服務
- Supabase - 資料庫服務

---

⭐ 如果這個專案對你有幫助，請給個 Star！

---

## 🔗 更多專案

查看我的完整作品集：[**tsoAI0305 Portfolio**](https://github.com/tsoAI0305/portfolio)

\# 📝 文字自訂指南



\## 💬 LINE Bot 訊息自訂



本工作流程的 LINE 訊息文字已英文化，請在 N8N 中自行修改為你想要的內容。



\### 需要自訂的節點



| 節點名稱 | 用途 | 建議文字 |

|---------|------|---------|

| Line: Send Welcome Message | 歡迎息 | "歡迎使用 AI 營養導航！" |

| Line: Ask Name | 詢問姓名 | "請輸入你的姓名" |

| Line: Ask Age | 詢問年齡 | "請輸入你的年齡" |

| Line: Ask Gender | 詢問性別 | "請選擇性別（男/女/其他）" |

| Line: Setup Complete | 設定完成 | "🎉 設定完成！" |



\### 自訂步驟



1\. 在 N8N 中開啟工作流程

2\. 點擊任一 LINE 訊息節點

3\. 修改 `jsonBody` 中的 `text` 欄位

4\. 儲存並測試



\### 範例



原始（佔位符）：

```json

"text": "Message text - please customize in N8N"

```



修改為：

```json

"text": "歡迎使用 AI 營養導航！請選擇功能：\\n1. 即時搜尋\\n2. 行程規劃\\n3. 查詢歷史"

```



\---



\### 🔧 JavaScript 註解



所有 JavaScript 註解已替換為 `// Comment removed`，你可以：

\- 保持原樣（不影響功能）

\- 自行加入新的英文註解

\- 加入中文註解（但不要推送到 GitHub）



\---



\## ⚠️ 注意事項



\- 修改文字不會影響工作流程邏輯

\- 建議在本地測試後再部署

\- 如果要分享修改後的版本，記得先清理 API Keys


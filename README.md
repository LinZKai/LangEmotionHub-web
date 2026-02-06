# LangEmotionHub Web

LangEmotionHub Web 是 LangEmotionHub 智慧語言模型訓練平台的前端應用，提供情感陪伴、個人模型訓練與記憶保存等核心功能的操作介面。

本平台以**語意鍛造**為核心概念，透過大型語言模型模擬特定對象的語言風格，讓使用者能夠重現對話情境、保存回憶，並獲得更貼近個人風格的情感互動體驗。



## 專案理念

LangEmotionHub 起源於對高齡化社會與情感陪伴需求的觀察，目標是透過 AI 技術實現：

- 模擬親友語言風格
- 保存長者智慧與回憶
- 提供個性化情感陪伴
- 結合 RAG 技術強化語境理解

本 Repo 為整體系統中的 Web App 前端應用層。



## 系統架構定位

前端負責：

- 使用者操作流程與畫面呈現
- 模型訓練資料上傳介面
- 聊天互動介面
- 記事本與情感標籤管理
- 與後端模型服務 API 串接

後端專案請參考：  
👉 [LangEmotionHub-api]()



## 核心功能

使用者可以透過本系統：

### 💬 個性化聊天模型
- 上傳聊天紀錄進行模型微調
- 模擬特定對象語言風格
- 分享個人模型給親友使用

### 📝 事件記事本（RAG）
- 建立事件與人物記錄
- 加入情感標籤
- 作為模型生成回應時的語境強化資料

### 👤 帳戶管理
- 註冊與登入
- 個人資料管理
- 密碼重設



## 技術架構

- React
- JavaScript (ES6+)
- RESTful API 串接

專案採模組化設計，將頁面層與可重用元件分離，讓功能可以獨立演進並降低頁面層複雜度。



## 專案結構概覽

src/

 ├── components/ # 可重用 UI 與功能元件

 ├── routes/ # 各頁面容器與路由守門元件（PrivateRoute）

 ├── utils/ # API 呼叫與工具函數封裝

 └── index.js # 應用入口與 React Router 設定

- `routes` 目錄負責頁面層結構
- 細部 UI 與邏輯拆分於 `components`
- 所有路由設定集中於 `index.js`



## 安裝與執行

```bash
npm install
npm start
```



## 系統畫面預覽

### 1.上傳訓練資料與模型訓練介面
<img width="1890" height="348" alt="image" src="https://github.com/user-attachments/assets/fdcff7eb-167b-418e-87d3-4de9adb25285" />

### 2.個性化聊天模型介面
<img width="1656" height="828" alt="image" src="https://github.com/user-attachments/assets/cd72b78a-f04a-4875-98f5-1965ee03d1e5" />

### 3.事件記事本介面
<img width="1644" height="424" alt="image" src="https://github.com/user-attachments/assets/79c3d142-bd9a-48e6-9f3d-c318c71bec32" />



## 專案背景與團隊
LangEmotionHub 為國立政治大學資訊管理學系 2024 年畢業專題專案，由團隊共同開發完成。

本 Repo 為前端 Web App 部分，整理後於個人帳號重新建立，用於作品展示。



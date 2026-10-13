<img src="./assets/profile-banner.svg" width="100%" alt="林奕辰 Yi-Chen Lin — Information Systems, Backend, Data-Driven Applications" />

<div align="center">

### 國立雲林科技大學・資訊管理系二技
**軟體系統｜後端開發｜資料驅動應用｜系統整合**

</div>

---

## 我在做什麼

我喜歡先從**真實流程裡的問題**出發，再把資料、程式與系統架構串起來。

目前最常碰到的題目不是「做一個功能」，而是：

> **資料怎麼來 → 怎麼整理 → 怎麼判斷 → 怎麼讓系統可靠地使用 → 最後怎麼讓人做決策**

這也是我現在最想繼續深化的方向：  
**Software Systems / Data-Driven Applications / Intelligent Information Systems / System Integration**

---

## 目前重點

| 主題 | 我在處理的問題 | 代表實作 |
|---|---|---|
| **系統整合** | 不同 API、不同資料格式、不同服務限制如何整合 | 跨國公共運輸資訊整合服務 |
| **資料處理** | 資料標準化、比對、驗證與異常判斷 | 營造工程量價估算與異常偵測 |
| **智慧應用** | OCR / Computer Vision 如何放進實際工作流程 | 旅客證件 OCR、無人機影像辨識 |
| **可靠性** | 快取、額度、fallback、人工覆核 | 交通資訊服務、OCR 審核流程 |

---

## 精選專案

### 01｜跨國公共運輸資訊整合服務
[**Cross-Border Public Transportation Information Service → Repository**](https://github.com/YI-CHENLIN1204/travel-info-assistant)

整合台灣、東京、香港、新加坡等不同城市與運輸系統的資料來源，後端負責資料格式統一與服務整合，並透過快取、限流、額度控制與 fallback 降低重複請求與外部 API 消耗。

`Vue 3` `TypeScript` `ASP.NET Core` `PostgreSQL` `Redis` `REST API` `Docker`

---

### 02｜旅客證件 OCR 辨識與資料管理系統
**Travel Document OCR & Data Management System**

源自旅行社實際證件建檔流程，將人工輸入改成：

`證件上傳 → OCR → 欄位驗證 → 旅客比對 / 合併 → 人工覆核`

核心重點不是單純「辨識文字」，而是把 OCR 結果變成可以實際使用的旅客資料。

`Vue 3` `TypeScript` `ASP.NET Core` `PostgreSQL` `PaddleOCR.js / PP-OCRv5` `Docker`

> Repository 目前維持 Private，避免隱私敏感測試資料與證件處理流程被直接公開。

---

### 03｜營造工程量價估算與異常偵測系統
**Construction Cost Estimation & Anomaly Detection System**

產學合作專案。負責資料標準化、相似案例分析、歷史樣本處理、量價估算與異常偵測，目標是把歷史工程資料轉化為**可以支援人工判斷的參考依據**。

`C#` `ASP.NET Core` `EF Core` `PostgreSQL` `Vue` `REST API` `Docker`

> 因涉及合作資料與專案限制，原始碼不公開。

---

### 04｜無人機結合影像辨識
**Drone-Based Image Recognition System**

五專畢業專題，擔任專題組長。整合影像辨識、嵌入式控制、無線通訊、3D 建模與硬體除錯，完成小型四軸無人機系統。

`Python` `TensorFlow` `Keras` `OpenCV` `Arduino` `MultiWii` `NRF24L01` `3D Printing`

---

## 技術工具箱

**Backend**  
C# / ASP.NET Core / Entity Framework Core / REST API

**Programming & Data**  
Python / Java / SQL / Data Validation / OCR / Image Processing

**Database & Infrastructure**  
PostgreSQL / MySQL / Redis / Docker / Git / GitHub / Linux

**Frontend**  
JavaScript / TypeScript / Vue / HTML / CSS

---

## 我的學習脈絡

```text
資訊工程基礎
    ↓
軟硬體整合與影像辨識
    ↓
後端 / API / 資料庫 / 系統整合
    ↓
資料品質、規則設計、異常判斷
    ↓
希望進一步建立研究方法與系統評估能力
```

我目前最在意的，不只是「功能有沒有做出來」，而是：

- 問題是否定義正確
- 資料是否可靠
- 方法是否能被驗證
- 系統是否真的改善原本的流程

---

## 專業認證

**AWS Certified Cloud Practitioner**  
**ISC2 Certified in Cybersecurity (CC)**  
**Microsoft Azure AI Fundamentals (AI-900)**  
**Google Data Analytics Professional Certificate**  
**TQC+ Python 3**

---

## GitHub

目前公開的主要開發專案以 **travel-info-assistant** 為主；  
其餘涉及個資、產學合作或歷史專題的專案，會依資料敏感度與授權狀況決定是否公開。

<div align="center">

**持續把問題拆開、把資料整理好、把系統做得更可靠。**

</div>
# 🧶 Crochet Pattern Recognition System  
### 鉤織圖案即時辨識系統（Real-time）

---

## 📌 專案簡介（Overview）

本專案為銘傳大學資訊工程學系畢業專題，針對鉤織（Crochet）藝術中複雜且細微的針法圖案，利用 YOLOv8 深度學習演算法進行即時影像辨識。  

本專案整合 YOLOv8 與 Flask 架構，實現一套可即時上傳圖片並進行針法辨識的 Web 系統，協助使用者快速理解鉤織圖樣。

---

## 🛠 技術棧（Tech Stack）

- Programming Language: Python  
- AI Model: YOLOv8 (Ultralytics)  
- Deep Learning: PyTorch  
- Computer Vision: OpenCV  
- Backend: Flask  
- Frontend: HTML / CSS / JavaScript  
- Database: SQLite  
- Tools: LabelImg, Git  

---

## 🚀 技術亮點（Technical Highlights）

- **細粒度圖案辨識**：  
  針對鉤織圖案中高重複性與細微差異的針法特徵（如 ch、sc、dc），提升模型辨識能力。  

- **資料增強（Data Augmentation）**：  
  透過旋轉、縮放等方式擴充資料集，提高模型在不同環境下的穩定性。  

- **資料集建構與標註**：  
  使用 LabelImg 建立專用鉤織資料集，提升辨識準確度。  

- **辨識結果視覺化**：  
  透過 YOLOv8 將辨識結果以 Bounding Box 呈現，使結果更直觀。  

---

## 🧩 系統功能（System Features）

### 🔍 圖片辨識功能（Image Recognition）
- 上傳鉤織圖片進行針法辨識  
- 支援本地圖片上傳與拍照上傳  
- 自動辨識針法種類（如 ch、sc、dc）  
- 統計各針法數量  

### 🖼 輸出結果控制（Output Options）
- 可選擇輸出原始圖片  
- 可選擇輸出辨識結果（Bounding Box）  

### ⚙️ 使用者操作（User Interaction）
- 圖片上傳與選擇介面  
- 一鍵開始辨識  
- 即時顯示結果  

### 📜 歷史紀錄（History System）
- 查看「我的結果」  
- 儲存與回顧辨識紀錄  

### 📚 教學功能（Learning Support）
- 提供針法教學內容  
- 協助理解辨識結果  

### ℹ️ 系統資訊（System Information）
- 使用說明  
- 關於系統介紹  

### 👤 使用者系統（User System）
- 顯示登入資訊  
- 管理個人紀錄  

### 🎨 介面設計（UI / UX Features）
- 圖片上傳區  
- 操作按鈕（辨識 / 拍照）  
- 卡片式設計  
- 響應式介面（支援手機）  

---

## 📊 成果展示（Demo）

<p align="center">
  <img src="./image/demo1.png" width="30%"/>
  <img src="./image/demo2.png" width="30%"/>
  <img src="./image/demo3.png" width="30%"/>
</p>

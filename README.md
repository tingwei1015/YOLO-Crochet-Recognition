# 🧶 鉤織圖案即時辨識系統  
**Real-time Crochet Pattern Recognition System**

## 📌 Overview
本專案為銘傳大學資訊工程學系畢業專題，針對鉤織（Crochet）圖案中複雜且細微的針法結構，設計一套基於深度學習之即時影像辨識系統。  

透過 YOLOv8 物件偵測模型，系統可自動辨識不同針法（如 ch、sc、dc 等），協助使用者快速理解鉤織圖樣，解決傳統手工辨識困難與計數不易的問題。  

---

## 🛠 Tech Stack

- **AI Model**: YOLOv8 (Ultralytics)  
- **Programming Language**: Python  
- **Deep Learning Framework**: PyTorch  
- **Computer Vision**: OpenCV  
- **Web Framework**: Flask  
- **Frontend**: HTML / CSS / JavaScript  
- **Database**: SQLite  
- **Tools**: LabelImg, Git  

---

## 🚀 Technical Highlights

### 🔹 Fine-grained Feature Recognition
針對鉤織圖案中高重複性與細微差異的針法特徵，進行資料增強（Data Augmentation），提升模型在不同環境下的辨識穩定性與準確率。  

### 🔹 Real-time Detection System
整合 YOLOv8 與 Flask 架構，實現影像上傳、即時偵測與結果視覺化，具備實際應用價值。  

### 🔹 Full-stack Development
結合前端（HTML/CSS/JavaScript）與後端（Flask），完成完整 Web 系統開發，包含圖片上傳、偵測結果顯示與使用者操作介面設計。  

### 🔹 Dataset Construction
自行蒐集並標註鉤織圖像資料，使用 LabelImg 建立專用資料集，提升模型對不同針法的辨識能力。  

---

## 📊 Demo
（建議放成果圖片或 GIF）

---

## 📬 Contact
（可選填：你的 Email 或 GitHub）

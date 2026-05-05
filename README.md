# 🧶 Crochet Pattern Recognition System  
### 鉤織圖案即時辨識系統（Real-time）

---

## 📌 專案簡介（Overview）

本專案為銘傳大學資訊工程學系畢業專題，針對鉤織（Crochet）藝術中複雜且細微的針法圖案，利用 YOLOv8 深度學習演算法進行即時影像辨識。  

本專案整合 YOLOv8 與 Flask 架構，實現一套可即時上傳圖片並進行針法辨識的 Web 系統。系統可自動識別不同鉤織紋路，解決手工藝初學者難以分辨針法與計算針數的問題。

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

- **複雜紋理處理能力**：  
  鉤織物具有高度柔軟性與精細紋理，專案中針對「針法特徵」進行 Data Augmentation，提升模型在不同角度與光線下的辨識能力。  

- **即時辨識系統**：  
  整合 YOLOv8 與 Flask 架構，實現影像上傳、即時偵測與結果視覺化，具備實際應用潛力。  

- **系統整合能力**：  
  結合前端（HTML / CSS / JavaScript）與後端（Flask），完成完整 Web 系統開發，包含圖片上傳、辨識結果顯示與操作介面設計。  

- **資料集建構能力**：  
  自行蒐集並標註鉤織資料集，確保模型對不同針法（如短針、長針）具備良好辨識能力。  

---

## 📊 成果展示（Demo）

![demo](./demo.png)

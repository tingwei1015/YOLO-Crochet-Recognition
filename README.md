# 🧶 鉤織圖案即時辨識系統（Real-time Crochet Pattern Recognition）

---

## 📌 專案簡介（Overview）

本專案為**銘傳大學資訊工程學系畢業專題**，針對鉤織（Crochet）藝術中複雜且細微的針法圖案，利用 **YOLOv8 深度學習演算法** 進行即時影像辨識。  
本系統旨在自動識別不同的鉤織紋路，解決手工藝初學者難以分辨針法、計算針數的痛點。

---

## 🛠 技術棧（Tech Stack）

- **AI Model**: YOLOv8（Ultralytics）  
- **Languages**: Python（模型訓練與系統開發）  
- **Computer Vision**: OpenCV  
- **Framework**: Flask  
- **Deep Learning**: PyTorch  
- **Frontend**: HTML / CSS / JavaScript  
- **Database**: SQLite  
- **Tools**: LabelImg、Git  

---

## 🚀 技術亮點（Technical Highlights）

- **複雜紋理處理**：  
  鉤織物具有高度柔軟性與精細紋理，專案中針對「針法特徵」進行 Data Augmentation，提升模型在不同角度與光線下的辨識能力。  

- **即時辨識系統**：  
  整合 YOLOv8 與 Flask 架構，實現影像上傳、即時偵測與結果視覺化，具備實際應用潛力。  

- **系統整合能力**：  
  結合前端（HTML / CSS / JavaScript）與後端（Flask），完成完整 Web 系統開發，包含圖片上傳、辨識結果顯示與操作介面設計。  

- **資料集建構**：  
  自行蒐集並標註鉤織資料集，確保模型對不同針法（如短針、長針）具備良好辨識能力。  

---

## 📊 成果展示（Demo）

> （建議放一張辨識成功圖片，面試會很加分）

# 鉤織圖案即時辨識系統 (Real-time Crochet Pattern Recognition)

## 📌 專案簡介 (Overview)
本專案為 **銘傳大學資工系畢業專題**。
針對鉤織（Crochet）藝術中複雜且細微的針法圖案，利用 **YOLOv8** 深度學習演算法進行即時影像辨識。本系統旨在自動識別不同的鉤織紋路，解決手工藝初學者難以分辨針法、計算針數的痛點。

## 🛠️ 技術棧 (Tech Stack)
- **AI Model:** YOLOv8 (Ultralytics)
- **Languages:** Python (模型訓練與驗證), **C++** (規劃推論優化方向)
- **Computer Vision:** OpenCV
- **Tools:** LabelImg, Git, PyTorch

## 🚀 技術亮點 (Technical Highlights)
- **複雜紋理處理:** 鉤織物具有高度柔軟性與精細紋理，專案中針對「針法特徵」進行了 Data Augmentation，提升模型在不同角度與光線下的魯棒性。
- **效能導向思考:** 雖然訓練端使用 Python，但身為具備 **C++ 精通** 能力的開發者，我預留了模型部署至 C++ 環境的介面，未來可透過 **TensorRT** 或 **OpenVINO** 進一步提升推論速度（FPS）。
- **資料集工程:** 自行標記並清理鉤織專用資料集，確保模型對「短針」、「長針」等相似圖案具備高鑑別度。

## 📈 成果展示 (Demo)
*(建議在這裡上傳一張辨識成功的截圖，面試官非常看重這個！)*

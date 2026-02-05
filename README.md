# semiconductor-defect-classification-iesa
Edge-AI Semiconductor Defect Classification - IESA DeepTech Hackathon Phase 1
## 📥 Download Model Files

Model files (too large for GitHub) are hosted on Google Drive:

**[📦 Download Models Here](https://drive.google.com/drive/folders/1WzHY1R_6HQ6rHOu-c5hxWhff3PmPOaBK?usp=sharing)**

**Files included:**
- `best_model.h5` (7.52 MB) - Trained Keras model  
- `defect_classifier.onnx` (5.82 MB) - ONNX format for edge deployment

**How to use:**
1. Download both files from the link above
2. Place them in the `models/` directory
3. Run inference: `python src/predict.py --model models/best_model.h5 --image test.png`

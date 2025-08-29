# Skin Cancer Classification using CNN

## 📌 Overview
This project builds a Convolutional Neural Network (CNN) to classify skin cancer images into different categories. The objective is to leverage deep learning for accurate diagnosis support and assist in early detection of skin cancer.

## 📊 Dataset
- **Source:** Kaggle – Skin Cancer Dataset
- **Content:** Dermoscopic images of skin lesions
- **Classes:** Multiple categories of skin cancer (e.g., Melanoma, Basal cell carcinoma, etc.)

## ⚙️ Approach
1. **Data Preprocessing:**
   - Resized and normalized images.
   - Applied **data augmentation** to increase dataset diversity.

2. **Model Building:**
   - Implemented a **CNN** with convolutional, pooling, and dense layers.
   - Used **Batch Normalization** for stable training.
   - Applied **Dropout** to reduce overfitting.

3. **Training & Optimization:**
   - Optimized using Adam optimizer and categorical cross-entropy loss.
   - Evaluated with metrics like accuracy, precision, recall, and F1-score.

## 🚀 Results
- CNN achieved strong classification performance on skin lesion images.
- Batch Normalization and Dropout improved generalization.
- Model demonstrates potential for real-world clinical decision support.

## 📂 Project Structure
```
├── Skin Cancer.ipynb     # Jupyter Notebook with code and experiments
├── README.md             # Project documentation
```

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/skin-cancer-classification-cnn.git
   cd skin-cancer-classification-cnn
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook "Skin Cancer.ipynb"
   ```

## 📌 Future Improvements
- Use transfer learning with pre-trained models (ResNet, VGG, EfficientNet).
- Deploy as a web app for interactive predictions.
- Incorporate explainability (Grad-CAM) for better insights.

---

🔗 *Feel free to fork and improve this project!*

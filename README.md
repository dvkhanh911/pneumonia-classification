# Pneumonia Classification from Chest X-ray Images using Deep Transfer Learning and Weighted Ensemble

## Overview

Pneumonia is a serious respiratory infection caused by bacteria or viruses, commonly observed in developing countries with limited healthcare infrastructure. Early diagnosis plays a crucial role in improving survival rates and treatment outcomes.
Chest X-ray imaging is the most widely used diagnostic tool for pneumonia detection. However, manual interpretation is time-consuming and subject to variability among radiologists.
This project proposes an automated computer-aided diagnosis (CAD) system for pneumonia classification using deep transfer learning and a weighted ensemble of convolutional neural networks (CNNs).

---

## 🎯 Objectives

This study focuses on the following key aspects:

- Implement and compare three powerful CNN architectures using transfer learning:
  - ResNet50
  - DenseNet169
  - EfficientNet-B0
- Develop a weighted average ensemble method, where model weights are automatically determined based on validation performance.
- Apply Grad-CAM visualization to interpret and highlight important image regions influencing model decisions.

---

## 📊 Dataset

The model is trained and evaluated on a combination of two public datasets:

- [Kermany et al. Chest X-ray dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) 
- [Kumar dataset](https://data.mendeley.com/datasets/dvntn9yhd2/1)

These datasets contain labeled chest X-ray images for pneumonia and normal cases.

---

## 📈 Results

The proposed ensemble model achieved:

**Accuracy: 98.86%**

This demonstrates strong performance compared to many existing single-model approaches.

---


## 📂 Project Structure

```
├── DataPreprocessing.ipynb
├── pneumonia-classification.ipynb
├── README.md
├── .gitignore
```

---

## 🚀 How to Run

1. Install required dependencies  
2. Run `DataPreprocessing.ipynb`  
3. Run `pneumonia-classification.ipynb` to train and evaluate models  


## 📌 Conclusion

This project demonstrates that combining deep transfer learning with a weighted ensemble strategy significantly enhances pneumonia classification performance. The integration of Grad-CAM further improves interpretability, making the system more reliable for medical applications.

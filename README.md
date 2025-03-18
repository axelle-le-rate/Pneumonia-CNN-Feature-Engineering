# 🔬 Pneumonia Feature Engineering & Exploratory Data Analysis (EDA)  

## 📌 Project Overview  
This project explores **feature engineering techniques** and **exploratory data analysis (EDA)** to improve **pneumonia detection** from chest X-ray images. The goal is to extract meaningful image features, visualize key patterns, and enhance the performance of machine learning models.  

## 🗂️ Dataset  
- **Source**: [Chest X-ray Dataset (Kaggle)](https://www.kaggle.com/datasets)  
- **Size**: 5,800+ labeled images (`Normal` / `Pneumonia`)  

## 🏗️ Feature Engineering & EDA Techniques  
- 📊 **Data Exploration**: Distribution of pneumonia vs. normal cases, missing data handling  
- 🏞️ **Image Processing**: Resizing, grayscale conversion, histogram equalization  
- 📈 **Feature Extraction**:  
  - Texture-based features (GLCM, LBP)  
  - Edge detection (Canny, Sobel filters)  
  - Statistical features (mean, variance, entropy)  
- 📉 **Dimensionality Reduction**: PCA, t-SNE for visualization  
- 🤖 **Preliminary Model Testing**: Feature importance analysis for ML models  

## 🔍 Key Findings  
- Certain texture patterns are more prominent in pneumonia cases.  
- Edge detection reveals differences in lung structure.  
- PCA/t-SNE visualizations show distinct clusters for normal vs. pneumonia cases.  

## 🚀 How to Run the Project  

1. **Clone the repository**:  
   ```sh
   git clone https://github.com/YourGitHubUsername/Pneumonia-Feature-Engineering-EDA.git

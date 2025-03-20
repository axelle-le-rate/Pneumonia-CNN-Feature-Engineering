# 🔬 Pneumonia Feature Engineering & Exploratory Data Analysis (EDA)  

## 📌 Project Overview  
This project explores **feature engineering techniques** and **exploratory data analysis (EDA)** to improve **pneumonia detection** from chest X-ray images. The goal is to extract meaningful image features, visualize key patterns, and enhance the performance of machine learning models.  

## 🗂️ Dataset  
- Source: **[Chest X-ray Dataset (Kaggle)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)**  
- Data Size: **5,800+ labeled images** (Normal/Pneumonia)    

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
   
2. **Install dependencies**:
This project uses the following Python libraries:
- TensorFlow
- Keras
- OpenCV
- Matplotlib
- os
  
To install these dependencies, use:
```pip install -r requirements.txt  ```
3. **Running the Jupyter Notebook** :
Once you've cloned the repo and installed the dependencies, you can open and run the Jupyter Notebook.
- Navigate to the directory where the repo is cloned.
- Start Jupyter Notebook by running:
 ```sh
jupyter notebook
 ```
Open the Pneumonia_Feature_Engineering.ipynb file, and run all the cells in the notebook.

## ⚙️ Technologies Used
Python · NumPy · Pandas · OpenCV · Matplotlib · Scikit-learn · Scikit-Image · SciPy

## 📌 Future Improvements
- Explore deep learning-based feature extraction using CNNs.
- Compare handcrafted vs. automated features for ML performance.
- Use ensemble models to enhance prediction accuracy.

## 📝 Note on ChatGPT Assistance
During the development and debugging phases of this project, I referenced valuable conversations with ChatGPT that helped me resolve coding issues and improve the overall solution. Unfortunately, these conversations are no longer accessible due to platform limitations, so the specific details cannot be provided here. However, the guidance and debugging steps from those interactions were integral to the project.

# 🎯 **Heart Disease Prediction Model**  
Predict the likelihood of heart disease based on clinical and demographic data using machine learning.

---

## 📝 **Problem Statement**  
Heart disease is a leading cause of death worldwide, and early detection is crucial for effective treatment and prevention. This project aims to predict the presence of heart disease using a **Logistic Regression Model**, providing a simple yet effective tool for medical decision-making.

---

## 📂 **Dataset**  
- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/) or [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Description**:  
  - **Features**:  
    - `Age`: Age of the patient  
    - `Sex`: Gender of the patient  
    - `CP`: Chest pain type (categorical)  
    - `Trestbps`: Resting blood pressure  
    - `Chol`: Serum cholesterol in mg/dl  
    - `FBS`: Fasting blood sugar > 120 mg/dl (binary)  
    - `Thalach`: Maximum heart rate achieved  
    - `Exang`: Exercise-induced angina (binary)  
    - Other clinical measurements  
  - **Target**: `Presence of Heart Disease`  
    - `1`: Heart disease present  
    - `0`: Heart disease not present  

---

## 🛠️ **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - `pandas` - Data manipulation  
  - `numpy` - Numerical computations  
  - `matplotlib` & `seaborn` - Data visualization  
  - `scikit-learn` - Machine learning implementation  

---

## 🔍 **Project Workflow**  
1. **Data Preprocessing**:  
   - Load and inspect the dataset.  
   - Handle missing or inconsistent data.  
   - Encode categorical variables (e.g., `Chest Pain Type`, `Exercise Angina`).  
   - Normalize numerical features for better model performance.  

2. **Exploratory Data Analysis (EDA)**:  
   - Analyze correlations between features and target variable.  
   - Visualize data using histograms, scatter plots, and heatmaps.  

3. **Model Building**:  
   - Split the dataset into training and testing sets.  
   - Train a **Logistic Regression Model** on the training data.  
   - Evaluate model performance using metrics such as **accuracy, precision, recall, and F1-score**.  

4. **Prediction**:  
   - Test the model on unseen data.  
   - Predict the likelihood of heart disease for new patients.  

---

## 📊 **Results**  
- **Model Used**: Logistic Regression  
- **Performance Metrics**:  
  - **Accuracy**: 86.7%  
  - **Precision**: 0.89  
  - **Recall**: 0.85  
  - **F1-Score**: 0.87  

---

## 🌐 **Run on Google Colab**  
You can run this project directly on Google Colab without setting up anything locally.  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eJ41BRU3Oz-EbBUqA1xlymH-9hBm_gG6)

---

### Steps to Run on Google Colab:  
1. Click the **"Open in Colab"** button above.  
2. Upload the dataset if not provided in the notebook.  
3. Run all the cells sequentially.  
4. View results directly in your browser.  

---

### Note  
- Ensure that the dataset is accessible in the notebook.  
- Trained models and predictions can be downloaded from the Colab interface if required.  

---

## 🔮 **Future Enhancements**  
- Experiment with advanced models like Random Forest or Gradient Boosting for improved accuracy.  
- Include additional features such as family medical history or lifestyle factors.  
- Perform hyperparameter tuning to optimize the Logistic Regression model.  

---

## 📚 **References**  
- [Scikit-learn Documentation](https://scikit-learn.org/)  
- [Kaggle Heart Disease Dataset](https://www.kaggle.com/)  
- [World Health Organization - Heart Disease Statistics](https://www.who.int/)  

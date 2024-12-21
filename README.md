# 🍷 **Wine Quality Feature Selection Analysis**

Welcome to the **Wine Quality Feature Selection** project! This repository demonstrates the use of feature selection techniques to identify the most relevant features that influence the quality of red wine.

---

## 📊 **Project Overview**

This project analyzes the **`winequality_red.csv`** dataset, which contains various chemical properties of red wines and their quality ratings (from 0 to 10). The focus is on selecting the most significant features that contribute to wine quality prediction, ensuring that the model uses only the most relevant data.

### Key Highlights:
- **Dataset**: 1,599 rows and 12 columns
- **Focus**: Feature selection to improve model efficiency and accuracy
- **Techniques Used**: Variance Threshold, Correlation Analysis, Information Gain

---

## 🔧 **Technologies Used**

- **Python**: Primary language for data analysis
- **Pandas**: For data manipulation and cleaning
- **NumPy**: For numerical operations
- **Matplotlib**: For data visualization
- **Seaborn**: For statistical plotting and visualizations

---

## 🔍 **Feature Selection Process**

### **1. Dataset Overview**
The dataset is free from missing values, ensuring the feature selection process is smooth and efficient.

---

### **2. Feature Selection Techniques**

- **VarianceThreshold**: Eliminated features with low variance, retaining only those with significant variability.
- **Correlation Analysis**: Identified highly correlated features and removed redundant ones to avoid multicollinearity.
- **Information Gain**: Calculate the importance of each feature relative to the target variable (quality).

---

### **3. Key Findings**

- **Top Features**: Features such as **alcohol**, **volatile acidity**, and **sulphates** emerged as the most influential in predicting wine quality.
- **Feature Reduction**: After applying variance thresholding and correlation analysis, the dataset was reduced by **30%** without losing important predictive information.

---

## 📸 **Visualizations**

Here are key visualizations from the feature selection process:

### **1. Correlation Heatmap**
The heatmap visualizes the correlation between features and the target variable, **quality**, helping us identify strong relationships and multicollinearity.

![Correlation Heatmap](https://github.com/abhinishtiwari/-Wine-Quality-Feature-Selection-Analysis/blob/da57f1f387f0f9464b04340f22def32681041a3c/Image/Features%20Based%20on%20Correlation%20Threshold.png)

### **2. Feature Importance Bar Chart**
After applying feature selection techniques, this bar chart shows the most important features for wine quality prediction.

![Information Gain For Regression](https://github.com/abhinishtiwari/-Wine-Quality-Feature-Selection-Analysis/blob/da57f1f387f0f9464b04340f22def32681041a3c/Image/Information%20Gain%20For%20Regression.png)

### **3. Information Gain**
This chart shows the Information Gain of the features selected for modeling, helping us understand their impact on the model.

![Information Gain](https://github.com/abhinishtiwari/-Wine-Quality-Feature-Selection-Analysis/blob/da57f1f387f0f9464b04340f22def32681041a3c/Image/Information%20Gain.png)

---

## ⚙️ **How to Use**

### **Installation**
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wine-quality-feature-selection.git
   ```
2. Navigate to the project folder:
   ```bash
   cd wine-quality-feature-selection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### **Running the Feature Selection**

1. Open `feature_selection_analysis.ipynb` or `feature_selection_analysis.py`.
2. Run the code to perform feature selection and generate the visualizations.

---

## 📝 **Conclusion**

This project highlights the importance of feature selection in improving model performance. By focusing on the most relevant features, such as **alcohol**, **volatile acidity**, and **sulphates**, we reduced the dataset size by **30%** while maintaining predictive accuracy.

Feel free to explore the analysis, contribute, or suggest improvements!

---

## 🤝 **Contributing**

We welcome contributions! Feel free to open an issue or create a pull request to improve the feature selection process.

# 🚀 E-commerce Product Performance Predictor 🛍️  

Welcome to the **E-commerce Product Performance Predictor** project! This comprehensive initiative analyzes and predicts the success of products listed on an e-commerce platform. By leveraging machine learning techniques, we aim to provide insights into product characteristics that drive sales, empowering sellers to make data-driven decisions. 📈  

---

## ✨ Project Overview  

This project includes the following key components:  

### 1️⃣ **Data Acquisition and Cleaning** 🧹  
- Initial data loading from a CSV file, removing duplicates and irrelevant columns.  
- Advanced text extraction from features like product descriptions to derive numeric and categorical data.  

### 2️⃣ **Exploratory Data Analysis (EDA)** 📊  
- In-depth correlation analysis to identify interdependencies between features.  
- Distribution analysis of key features to understand data patterns.  
- Feature engineering to enhance predictive models.  

### 3️⃣ **Feature Engineering & Selection** 🛠️  
- NLP techniques (e.g., tokenization, stemming) to extract features from product names.  
- Analysis of frequent words to create new features.  
- Feature selection by dropping low-impact features for efficiency.  

### 4️⃣ **Model Building & Evaluation** 🧠  
- Implemented models: Logistic Regression, Random Forests, Gradient Boosting, SVM, KNN.  
- Hyperparameter tuning using `GridSearchCV`.  
- Evaluated models with accuracy, confusion matrix, and classification reports.  
- Handled class imbalance using oversampling techniques.  

### 5️⃣ **Feature Importance Analysis** 🔍  
- Used logistic regression coefficients and Random Forest importance metrics to identify key features.  

### 6️⃣ **Interactive Product Prediction** 🔮  
- User input for predicting product success.  
- Deployed a prediction module for real-time classification.  

### 7️⃣ **Model Exportation** 📦  
- Exported trained models for future use.  

---

## 🧰 Libraries Used  
- **pandas**: Data manipulation and analysis.  
- **numpy**: Numerical operations.  
- **re**: Regular expressions for data cleaning and extraction.  
- **seaborn & matplotlib**: Insightful visualizations.  
- **nltk**: Natural Language Processing.  
- **scikit-learn**: Machine learning models, data preprocessing, hyperparameter tuning, and evaluation.  
- **imblearn**: Oversampling to handle class imbalance.  
- **joblib**: Saving and loading trained models.  
- **scipy**: Statistical analysis.  

---

## ⚙️ Key Steps  

### **Data Cleaning and Preprocessing**  
- Removed duplicate entries.  
- Extracted numeric data from 'Sold', 'Price', 'Reviews', and 'Rating' columns.  
- Converted 'Sold' to a binary variable (0 or 1).  
- Cleaned non-numeric values in 'Price', 'Reviews', and 'Rating'.  

### **Feature Engineering**  
- Tokenized and stemmed 'Product Name' for word-based features.  
- Analyzed most frequent words to identify important attributes.  
- Created dummy variables for product categories.  
- Conducted feature importance analysis using logistic regression coefficients.  
- Dropped low-impact and highly correlated features.  

### **Model Development**  
- Trained various machine learning models.  
- Optimized performance through hyperparameter tuning.  
- Evaluated using metrics like accuracy, classification reports, and confusion matrices.  

### **Interactive Prediction**  
- Enabled user interaction for product detail input.  
- Provided predictions for product success.  

### **Class Imbalance Handling**  
- Used oversampling techniques to address class imbalance in models.  

### **Model Evaluation**  
- Metrics: classification reports, confusion matrices, accuracy, and ROC curves.  

### **Model Export**  
- Exported models for reuse in future projects.  

---

## 🎯 Value & Use Cases  

- **Product Selection**: Identify product features driving success.  
- **Inventory Management**: Make informed stocking and promotion decisions.  
- **Marketing Strategies**: Optimize descriptions and campaigns for better conversions.  
- **Competitive Advantage**: Understand trends and outperform competitors.  
- **Data-Driven Decision-Making**: Provide actionable insights for product strategy.  

---

## 🚀 Let's Get Started!  

Explore the code, run the scripts, and contribute to this exciting project. Together, we can make e-commerce smarter and more efficient. Happy coding! 🎉  

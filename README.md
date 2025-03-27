# Electric Vehicle Classification Project

## 📌 Project Overview  
This project focuses on **predicting the type of Electric Vehicle (BEV vs. PHEV)** using **feature selection** and **machine learning models** while optimizing memory usage. The goal is to build an efficient classification model that provides accurate predictions based on vehicle characteristics.

---

## 📊 Dataset  
The dataset contains various attributes related to electric vehicles, such as:  
- **Vehicle Make & Model**  
- **Electric Vehicle Type (BEV or PHEV) - Target Variable**  
- **Electric Range**  
- **Base MSRP**  
- **Clean Alternative Fuel Vehicle (CAFV) Eligibility**  
- **Legislative District & Electric Utility**  

After preprocessing, we selected **relevant features** to improve model accuracy.

---

## ⚙️ Project Phases  

### **📍 Phase 1: Data Preprocessing & Feature Selection**  
- Handled **missing values** and **duplicates**  
- **Encoded categorical variables**  
- **Performed feature selection** to reduce dimensionality  
- Split dataset into **training (X_train, y_train) and testing sets (X_test, y_test)**  

### **📍 Phase 2: Exploratory Data Analysis (EDA)**  
- **Visualized class distributions** (BEV vs. PHEV)  
- **Analyzed correlations** between features  
- **Detected outliers** to refine data quality  

### **📍 Phase 3: Model Training & Evaluation**  
- Tested multiple classification models:  
  - **Random Forest**  
  - **Gradient Boosting**  
- Applied **Hyperparameter Tuning (GridSearchCV)**  
- Evaluated models using:  
  - **Accuracy, Precision, Recall, and F1-score**  
  - **Confusion Matrix & Classification Reports**  

### **📍 Phase 4: Final Model Selection & Deployment**  
- Selected the **best-performing model** based on evaluation metrics  
- Built a **machine learning pipeline** for deployment  
- **Saved the final model** 

---

## 🏆 Conclusion  

### **🔹 Key Findings**  
- Feature selection significantly **improved classification accuracy**  
- **Gradient Boosting** performed better than Random Forest for this dataset  
- Some features (e.g., **Electric Range**) had a strong impact on classification  

### **🔹 Recommendations for Improving Subscription Rates**  
- **Increase model interpretability** using SHAP values  
- **Collect more diverse EV data** to improve generalization  
- Implement **real-time prediction system**  

### **🔹 Future Recommendations**  
- Explore **Deep Learning models** for better accuracy  
- Integrate the model into a **web-based dashboard** for user interaction  

---

## 🙌 Thank You!  
For any questions or collaboration, feel free to reach out. 🚀  

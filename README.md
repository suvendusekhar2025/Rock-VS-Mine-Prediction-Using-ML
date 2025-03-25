# Rock-VS-Mine-Prediction-Using-ML
**Project Title: Rock vs. Mine Prediction Using Machine Learning**  

### **Project Overview:**  
This project focuses on predicting whether an object is a rock or a mine using machine learning techniques. The dataset used for this classification task is the Sonar dataset, which contains 208 rows and 61 columns in CSV format. The dataset consists of sonar signal readings, where each row represents an instance, and the features correspond to frequency-based attributes of the reflected signals.  

### **Objective:**  
The primary goal of this project is to develop a predictive model that can classify objects as either "rock" or "mine" based on the sonar signals received. Such classification models are particularly useful in underwater exploration, naval applications, and defense systems where identifying underwater objects accurately is crucial.  

### **Technologies & Dependencies Used:**  
- **Python Libraries:**  
  - **NumPy:** Used for numerical operations and handling array-based data.  
  - **Pandas:** Utilized for loading, exploring, and processing the dataset efficiently.  
  - **Scikit-Learn (sklearn):**  
    - **Train-Test Split:** Used for dividing the dataset into training and testing subsets to evaluate model performance.  
    - **Logistic Regression:** Employed as the classification model for predicting the target variable.  
    - **Accuracy Score:** Used to measure the performance of the trained model.  

### **Dataset Details:**  
- **Source:** Sonar dataset (CSV format)  
- **Total Samples:** 208 rows  
- **Total Features:** 60 numerical features + 1 target column  
- **Target Variable:** Binary classification (Rock or Mine)  

### **Methodology:**  
1. **Data Preprocessing:**  
   - The dataset was loaded using Pandas, and necessary preprocessing steps were applied.  
   - The target variable was encoded into binary labels (Rock = 0, Mine = 1).  

2. **Model Selection & Training:**  
   - The dataset was split into training and testing sets using an 80-20 ratio.  
   - The **Logistic Regression model** was chosen due to its efficiency in handling binary classification tasks.  
   - The model was trained on the training dataset.  

3. **Model Evaluation:**  
   - The performance of the trained model was evaluated using **accuracy score** from sklearn.metrics.  
   - The **training accuracy** was **83.4%**, indicating good model learning.  
   - The **test accuracy** was **76.2%**, reflecting the model's ability to generalize on unseen data.  

### **Conclusion:**  
The developed machine learning model effectively classifies sonar signals as either rock or mine with a satisfactory accuracy score. While Logistic Regression provided a reasonable performance, further improvements could be made by experimenting with advanced classification algorithms like Support Vector Machines (SVM), Random Forest, or Neural Networks. Feature engineering and hyperparameter tuning could also enhance accuracy for better real-world applicability.  




# **Online Payments Fraud Detection Using Machine Learning**  

## **Introduction**  
Online financial transactions have significantly increased with the rise of e-commerce, making fraud detection a critical necessity. This project implements advanced machine learning classification algorithms to detect fraudulent credit/debit card transactions with high accuracy.  

## **Features**  
### **Web Application Features**  
- **User Authentication**: Secure login system for users.  
- **Transaction Input**: User-friendly form for entering transaction details.  
- **Real-time Fraud Detection**: Predicts fraud likelihood for each transaction.  
- **Alerts & Notifications**: Generates alerts for suspected fraudulent transactions.  

### **Machine Learning Features**  
- **Classification Algorithms**: Implements Decision Tree, Random Forest, SVM, Extra Tree Classifier, and XGBoost.  
- **Model Training**: Uses historical transaction data for training.  
- **Performance Evaluation**: Assesses model accuracy using precision, recall, and F1-score.  
- **Model Persistence**: Saves trained models in `.pkl` format for real-time predictions.  

### **Deployment & Security**  
- **Flask Integration**: Backend API using Flask.  
- **IBM Cloud Deployment**: Hosted for scalability and accessibility.  
- **Data Security**: Uses encryption for secure data transmission and storage.  

## **Technology Stack**  
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask)  
- **Machine Learning**: Scikit-Learn, XGBoost, SMOTE  
- **Database**: PostgreSQL / MySQL (optional)  
- **Deployment**: IBM Cloud  

## **Installation & Setup**  
### **Prerequisites**  
Ensure you have the following installed:  
- Python 3.x  
- pip (Python package manager)  
- Flask (`pip install flask`)  
- Scikit-Learn (`pip install scikit-learn`)  
- XGBoost (`pip install xgboost`)  
- Pandas & NumPy (`pip install pandas numpy`)  
- imbalanced-learn (`pip install imbalanced-learn`)  

### **Steps to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/online-fraud-detection.git
   cd online-fraud-detection
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the Flask server:  
   ```bash
   python app.py
   ```  
4. Open the web application in a browser at `http://127.0.0.1:5000/`  

## **Usage**  
- Input transaction details in the web form.  
- Click "Predict" to get real-time fraud detection results.  
- Check logs and dashboards for detailed insights.  

## **Performance Evaluation**  
- **Accuracy Score**: Measures the overall correctness of fraud predictions.  
- **Confusion Matrix**: Shows classification performance.  
- **Precision & Recall**: Evaluates model performance in fraud detection.  

## **Advantages**  
✔️ High accuracy in fraud detection.  
✔️ Real-time fraud prediction.  
✔️ Adaptability to new fraud patterns.  
✔️ User-friendly web application.  

## **Limitations**  
⚠️ Model interpretability may be challenging.  
⚠️ Imbalanced datasets can affect prediction quality.  
⚠️ Computationally intensive for large-scale data.  



## **License**  
This project is licensed under the MIT License.  


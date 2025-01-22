# SMS Spam Detection System  

An advanced machine learning model designed to detect and classify SMS messages as spam or not spam. Built with **Python** and deployed using **Streamlit**, this project provides a user-friendly interface for real-time spam detection.  



## **Technology Stack**  
- **Python**: Core programming language.  
- **Scikit-learn**: Model building and evaluation.  
- **Pandas**: Data manipulation and preprocessing.  
- **NumPy**: Numerical computations.  
- **Streamlit**: Web application framework for deployment.  

---

## **Features**  
- **Data Collection**: Retrieval of labeled SMS messages dataset.  
- **Data Cleaning & Preprocessing**: Handling missing/duplicate values and text normalization.  
- **Exploratory Data Analysis (EDA)**: Insights and visualizations from dataset analysis.  
- **Model Development**: Implementation and evaluation of multiple machine learning classifiers.  
- **Web Deployment**: Streamlit-based application for real-time message classification.  

---

## **Dataset**  
The SMS Spam Collection dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset), consists of over **5,500 labeled SMS messages** categorized as either "spam" or "ham" (not spam).  

---

### **Data Cleaning & Preprocessing**  
- **Steps Involved**:  
  - Removal of null and duplicate values.  
  - Label encoding of the "type" column.  
  - Text normalization:  
    - Conversion to lowercase.  
    - Tokenization and stemming.  
    - Removal of special characters, stop words, and punctuation.  

### **Exploratory Data Analysis (EDA)**  
- Analyzed message properties such as character, word, and sentence counts.  
- Generated visualizations using **matplotlib** and **seaborn**, including:  
  - Bar charts, pie charts, and heatmaps.  
  - Word clouds for spam and ham messages.  
  - Frequency distribution of common spam words.  

---

### **Model Building & Selection**  
- **Algorithms Tested**:  
  - Naive Bayes  
  - Random Forest  
  - K-Nearest Neighbors (KNN)  
  - Decision Tree  
  - Logistic Regression  
  - Extra Trees Classifier  
  - Support Vector Classifier (SVC)  

- **Final Model**:  
  Achieved **100% precision** with the selected classifier, ensuring optimal spam detection while minimizing false positives.  

---

### **Web Deployment**  
The model is deployed using **Streamlit** for easy accessibility. Users can input an SMS message into a simple text box, and the app will predict whether it is spam or not spam.  

- **Live Demo**: Try the app [here](https://textsafe.streamlit.app/).  

---

## **Usage**  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-repo/sms-spam-detection.git  
   cd sms-spam-detection  
   ```  

2. **Install Dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. **Run the Application**:  
   ```bash  
   streamlit run app.py  
   ```  

4. **Access the App**:  
   Open your browser and visit `http://localhost:8501` to use the SMS Spam Detection model.  

---

## **Contributions**  
Contributions are welcome! If you encounter any issues or have suggestions for improvements:  
1. Open an issue describing the problem or enhancement.  
2. Submit a pull request with your proposed changes.  

---

## **License**  
This project is licensed under the **MIT License**.  




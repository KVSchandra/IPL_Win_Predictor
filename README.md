# **IPL Win Predictor**

## **Overview**
The **IPL Win Predictor** is a **machine learning-powered web application** that predicts the outcome of Indian Premier League (IPL) matches. By leveraging **historical match data, player statistics, and match conditions**, the app provides accurate predictions using a **trained ML model**.

## **Tech Stack**
- **Backend & ML**: Python, NumPy, Pandas, Scikit-Learn
- **Frontend**: Streamlit (for an interactive UI)
- **Deployment**: Heroku, GitHub Pages

## **Features**
✅ **ML-Based Predictions** – Predict IPL match outcomes using historical data  
✅ **User-Friendly UI** – Interactive and dynamic interface built with Streamlit  
✅ **Data Processing** – Efficient data handling with Pandas & NumPy  
✅ **Model Training** – Machine learning pipeline using Scikit-Learn  
✅ **Cloud Deployment** – Hosted on **Heroku** & **GitHub Pages** for accessibility  

## **Project Structure**
```
├── app1.py           # Main application file (Streamlit frontend)
├── pipe.pkl         # Trained ML model file
├── requirements.txt  # Required dependencies
├── procfile          # Deployment configuration for Heroku
├── setup.sh          # Setup script for deployment
```

## **Installation & Setup**
### **1. Clone the repository**
```bash
git clone https://github.com/KVSchandra/IPL_Win_Predictor.git
cd IPL_Win_Predictor
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Application**
```bash
streamlit run app1.py
```

## **Usage**
1. **Enter match details** – Select teams, venue, and other parameters.
2. **View predictions** – Get real-time winning probability insights.
3. **Analyze data** – Understand how different factors impact match outcomes.

## **Deployment**
The application is successfully deployed on **Heroku** and **GitHub Pages** for global accessibility.

## **Contributing**
Contributions are welcome! Fork the repository, create a new branch, and submit a pull request.

## **License**
This project is licensed under the **MIT License**.

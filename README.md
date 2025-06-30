
# 🏥 Medical Insurance Price Prediction using Machine Learning

This project predicts the **medical insurance cost** based on personal attributes such as age, gender, BMI, smoking status, and region using various **machine learning models** in Python.

## 📌 Project Overview

The aim of this project is to build a regression model to predict the cost of medical insurance using a dataset that contains information on individuals' demographic and health-related factors. It provides insights into how these factors influence insurance pricing.

## 📊 Dataset

The dataset used is from **Kaggle**: [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

### Columns:
- `age`: Age of the individual
- `sex`: Gender (male/female)
- `bmi`: Body Mass Index
- `children`: Number of children
- `smoker`: Smoking status (yes/no)
- `region`: Residential region (southwest, southeast, northwest, northeast)
- `charges`: Medical insurance cost (target variable)

## 🔧 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- LabelEncoder & OneHotEncoder
- Linear Regression / Random Forest / SVR / XGBoost

## 🧠 Models Applied

- **Linear Regression**
- **Support Vector Regression (SVR)**
- **Random Forest Regressor**
- **XGBoost Regressor**

## 📁 Project Structure

```bash
insurance-price-prediction/
│
├── insurance.csv                # Dataset
├── insurance_prediction.ipynb  # Jupyter Notebook with full code
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies
```

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/insurance-price-prediction.git
   cd insurance-price-prediction
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook insurance_prediction.ipynb
   ```

## 📈 Results

The performance of each model is evaluated using metrics like **R² Score** and **Mean Absolute Error (MAE)**. You can compare the models and choose the best-performing one.

## 🔮 Future Enhancements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Deploy the model using Streamlit or Flask
- Add more features such as medical history, exercise frequency, etc.
- Use deep learning models for better performance

## 🧾 License

This project is intended for educational purposes and is open-source. Feel free to fork and customize it.

---

## 🙋‍♂️ Acknowledgements

- Dataset: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Guide: [GeeksforGeeks Article](https://www.geeksforgeeks.org/machine-learning/medical-insurance-price-prediction-using-machine-learning-python/)

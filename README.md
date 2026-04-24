# 🏡 House-Price-Prediction-using-ML
ML-based house price prediction using feature engineering, EDA, Linear Regression, and Gradient Boosting.

This project focuses on predicting house prices using key features such as square footage, number of bedrooms, and location. It demonstrates a complete machine learning workflow, including data exploration, visualization, and model building to achieve high prediction accuracy.

---

## 📂 Project Structure

```bash
data/                         # Dataset used for training and testing
house_price_prediction.ipynb  # Main Jupyter Notebook with implementation
requirements.txt              # Python dependencies
README.md                     # Project documentation
```

---

## 📊 Dataset

The dataset contains detailed information about house listings, including:

- Number of bedrooms and bathrooms  
- Square footage (living area and basement)  
- Waterfront availability  
- Geographic coordinates (latitude, longitude, zipcode)  
- Year built and renovation details  
- Target variable: House price  

**Source:** _[Add dataset source or link here]_

---

## 🧪 Models Implemented

### 🔹 Linear Regression
- Used as a baseline model to understand relationships between features  
- Achieved approximately 73% accuracy  

### 🔹 Gradient Boosting Regressor
- An advanced ensemble technique based on decision trees  
- Significantly improved performance with ~91.94% accuracy  

---

## 📈 Key Visualizations

The project includes several visual insights, such as:

- Distribution of houses by bedroom count  
- Relationship between price and living area  
- Price variation across different locations  
- Impact of features like:
  - Basement area  
  - Number of floors  
  - Property condition  
  - Waterfront availability  

---

## 🔧 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

### 📦 Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/house-price-prediction.git
cd house-price-prediction
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the notebook**

```bash
jupyter notebook house_price_prediction.ipynb
```

---

## 🎯 Objective

To build a reliable machine learning model capable of accurately estimating house prices using regression techniques.

✅ The final model (Gradient Boosting) achieved ~91.94% accuracy.

---

## 📚 Key Learnings

- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature selection and engineering  
- Model building and evaluation  
- Performance comparison of regression models  

---

## 📌 Credits

Written by **Jhalak Agrawal**

---

## 🌟 Contribute

Feel free to fork this repository, enhance the model, or experiment with different datasets and algorithms.

---

## 📬 Contact

For any queries or collaboration opportunities, connect via GitHub.

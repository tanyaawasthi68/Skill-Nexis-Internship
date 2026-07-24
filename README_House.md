
# 🏡 House Price Prediction using Machine Learning

A beginner-friendly project to predict house prices based on various factors such as square footage, number of bedrooms, location, and more. This project walks through data exploration, visualization, linear regression, and gradient boosting to achieve high model accuracy.

---

## 📂 Project Structure

```

data/                         # Dataset used for training and testing
house_price_prediction.ipynb  # Main Jupyter Notebook with all code
requirements.txt              # Python dependencies
README.md                     # Project documentation

````

---

## 📊 Dataset

This dataset contains details of house listings including:

- Number of bedrooms and bathrooms  
- Square footage (with and without basement)  
- Waterfront presence  
- Location via latitude and longitude  
- Zipcode  
- Year built and renovated  
- Price of the house  

**Source:** _[Add dataset source or link here]_

---

## 🧪 Models Used

### 🔹 Linear Regression
- First model used to understand relationships in data  
- Achieved ~73% accuracy  

### 🔹 Gradient Boosting Regressor
- Powerful ensemble model using decision trees  
- Achieved **~91.94% accuracy**

---

## 📈 Key Visualizations

- Most common house types by bedroom count  
- Price vs. Living Area  
- Price vs. Location (Latitude and Longitude)  
- Influence of features like:
  - Basement area  
  - Floors  
  - Condition  
  - Waterfront  

---

## 🔧 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
````

### Main Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

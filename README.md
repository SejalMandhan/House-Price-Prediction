# 🏠 House Price Prediction using Linear Regression

This project is a simple Machine Learning model that predicts the **price of houses** based on various features such as area, number of bedrooms, furnishing status, and road access. It uses a linear regression algorithm from scikit-learn.

---

## 📌 Project Goals

- Learn how to preprocess real-world datasets
- Build a regression model using **scikit-learn**
- Predict house prices
- Evaluate the model using performance metrics

---

## 📂 Dataset

The dataset used is `Housing.csv`, which contains the following features:

- `area` — total area of the house
- `bedrooms` — number of bedrooms
- `bathrooms` — number of bathrooms
- `stories` — number of floors
- `mainroad` — whether the house has access to a main road (`yes`/`no`)
- `guestroom`, `basement`, `hotwaterheating`, `airconditioning` — yes/no fields
- `furnishingstatus` — categorical: furnished, semi-furnished, unfurnished
- `price` — the target variable (house price)

---

## 🧪 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn (Linear Regression, Label Encoding, Imputation)
- Jupyter Notebook

---

## ⚙️ How It Works

1. **Load the dataset**
2. **Convert categorical features** to numerical using LabelEncoder
3. **Impute missing values** using column-wise mean
4. **Split** the data into training and testing sets
5. **Train** a Linear Regression model
6. **Evaluate** the model using:
   - `R² Score` — measures model accuracy
   - `RMSE` — shows average prediction error

---

## ✅ Model Performance

| Metric       | Value           |
|--------------|-----------------|
| R² Score     | 0.649           |
| RMSE         | 1,331,071       |

---

## 📈 Example Output

python
R2 Score: 0.6494754192267804
RMSE: 1331071.4167895105


## 📥 Installation & Run


1. Clone this repo
git clone https://github.com/your-username/house-price-prediction.git

2. Install dependencies
pip install -r requirements.txt

3. Run the notebook
jupyter notebook House_Price_Prediction.ipynb

🙋‍♀️ Author
Sejal Mandhan
LinkedIn (www.linkedin.com/in/sejal-mandhan-a8b8302a6)



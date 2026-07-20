# Medical Insurance Cost Prediction using Multiple Linear Regression

## 📌 Objective

The objective of this project is to build a Multiple Linear Regression model that predicts medical insurance charges based on customer information such as age, sex, BMI, number of children, smoking status, and region. The project demonstrates the complete machine learning workflow, including data preprocessing, model training, prediction, and performance evaluation.

---

## 📂 Dataset

**Dataset Name:** Medical Cost Personal Insurance Dataset

**Source:** Kaggle

**Dataset Link:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

> Note: The dataset is not included in this repository. Please download it from the Kaggle link above.

---

## 🛠️ Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

Modules Used:
- LabelEncoder
- train_test_split
- LinearRegression
- mean_absolute_error
- mean_squared_error
- r2_score

---

## ⚙️ Methodology

1. Imported the required Python libraries.
2. Loaded the insurance dataset using Pandas.
3. Explored the dataset using `head()`, `info()`, and `describe()`.
4. Identified numerical features, categorical features, and the target variable.
5. Checked for missing values.
6. Encoded categorical variables (`sex`, `smoker`, and `region`) using Label Encoding.
7. Split the dataset into 80% training data and 20% testing data.
8. Trained a Multiple Linear Regression model.
9. Predicted insurance charges for the test dataset.
10. Evaluated the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
11. Visualized the results using an Actual vs Predicted scatter plot.

---

## 📊 Results

The Multiple Linear Regression model was successfully trained on the insurance dataset and evaluated using standard regression metrics.

Evaluation Metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The scatter plot comparing Actual vs Predicted insurance charges shows that the model is able to predict insurance costs reasonably well, although some prediction errors exist due to the linear nature of the model.

---

## ✅ Conclusion

This project demonstrates the use of Multiple Linear Regression for predicting medical insurance charges. Features such as age, BMI, smoking status, number of children, sex, and region contribute to the prediction of insurance costs. Among these, smoking status and BMI have a significant influence on the target variable. Although the model provides reasonable predictions, Linear Regression assumes a linear relationship between the input features and insurance charges, which may not fully capture complex real-world patterns. More advanced machine learning models can be explored to improve prediction accuracy.

---

## 📁 Repository Structure

```
Assignment-1/
│── Assignment-1.ipynb
│── README.md
```

---

##  Author
Name: Riya Shukla
Registration Number: 23BCE11293
Application Number: IN26012655
Batch Number: 2(B)

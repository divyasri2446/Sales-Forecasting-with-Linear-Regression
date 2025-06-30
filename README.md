# 📊 Sales Forecasting Using Linear Regression

## 🧠 Objective
To build a linear regression model that predicts future sales revenue based on historical chocolate sales data.

---

## 📁 Dataset
**File Used:** `Modified_Chocolate_Sales.csv`

### Columns:
- `Year`, `Month`: Time components
- `Product`: Chocolate product name
- `Boxes Shipped`: Quantity sold
- `Amount`: Total revenue

---

## ⚙️ Workflow

1. **Preprocessing**
   - Date column reconstructed from `Year` and `Month`
   - Missing values handled
   - One-hot encoding applied to the `Product` column

2. **Model**
   - Linear Regression via scikit-learn Pipeline
   - Time-based train/test split (80/20)

3. **Evaluation**
   - Plots of actual vs predicted sales
   - MSE and R² metrics for model performance

4. **Forecast**
   - Predict sales for the next 6 months
   - Visual and tabular representation of future predictions

---

## 📸 Output Screenshots Included

- 📈 `Actual vs Predicted Sales` plot  
- 📉 `Forecasted Sales (Next 6 Months)` chart  
- 🧾 `Tabular Forecast` of predicted future sales  

📂 All images are included in the repository under the `/screenshots` folder (or wherever you've stored them).

---

## 📽️ Demo
A screen recording with voice-over explains:
- Dataset and features
- Data preprocessing steps
- Model training and prediction
- Interpretation of outputs and forecast results

🎥 Included file: `sales_forecasting_demo.mp4`

---

## 📈 Results

- ✅ Model accurately captured sales patterns
- ✅ Future sales predicted per product
- ✅ Outputs visualized for easy understanding

---

## 📦 Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

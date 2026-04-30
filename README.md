## 📊 Summary & Key Findings

### 📌 Data Understanding

* The dataset contains multiple features influencing house prices such as size, location, and amenities.
* The target variable (price) is **highly skewed**, which required transformation.

---

### 🔄 Data Transformation

* Applied **log transformation** on price to reduce skewness.
* This improved model learning and stability.

---

### ⚙️ Model Performance

* A **Gradient Boosting Regressor** was used for prediction.
* The model captures non-linear relationships effectively.

---

### 📉 Evaluation (RMSE)

* RMSE was calculated after converting predictions back to original price scale.
* This ensures results are interpretable in real-world units (₹).

👉 Interpretation:

* RMSE represents the average deviation between predicted and actual prices.
* Example: RMSE = ₹800,000 means predictions are off by ~₹8 lakhs on average.

---

### 🔁 Model Stability

* Cross-validation was used to validate model consistency.
* Similar CV RMSE and test RMSE indicate good generalization.

---

### 📈 Feature Insights

* Feature importance analysis highlights key drivers of house prices.
* Location, size, and property-related attributes are major contributors.

---

## 🚀 Conclusion

This project demonstrates the importance of:

* Proper data preprocessing
* Log transformation for skewed targets
* Advanced models like Gradient Boosting

With correct evaluation and feature handling, the model provides reliable predictions suitable for real-world applications.



# 📱 Digital Diet & 🧠 Mental Health Classification

This project explores how digital habits affect mental health. It uses machine learning to predict mental health levels based on behavioral and lifestyle inputs.

## 📊 Features Used

### 🔢 Numerical:
- `screen_time_hours` ⏰
- `sleep_quality` 😴
- `caffeine_intake_mg_per_day` ☕
- `stress_level` 😰

### 🧬 Categorical:
- `age_group` 👶🧑👵
- `gender` 🚻

## 🎯 Target Variable

- `mental_health_score`: Synthetic score reflecting overall mental health
- `mh_category`: Categorized as **Low**, **Medium**, or **High** mental wellness

## 🛠️ Workflow

1. 🧹 Data Cleaning & Type Conversion
2. 🧠 Feature Engineering: `mental_health_score`
3. 🧮 Binning: Categorize scores into mental health levels
4. 🧪 Preprocessing:
    - Imputation of missing values
    - Standardization of numeric features
    - One-hot encoding of categorical features
5. 🌲 Modeling with Random Forest Classifier
6. 📈 Evaluation using classification metrics

## 🧪 Example Usage

```python
# Train the model
clf_pipeline.fit(X_train, y_train)

# Predict and evaluate
y_pred = clf_pipeline.predict(X_test)
print(classification_report(y_test, y_pred))
```

## 🧰 Requirements

- pandas 🐼
- numpy 🔢
- scikit-learn 🤖

## 👤 Author

Crafted with ❤️ to understand digital well-being through data.


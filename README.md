# Predicting Hotel Booking Cancellations through Data Science

> NTU Data Science Mini Project  
> Lab Group: TEL1_team 2  
> Team Members: [Your Full Names]

---

## 🎯 Motivation

In this project, we aimed to solve the following problem:

**Problem Definition:**  
Clearly state what you're predicting/classifying/detecting (e.g., "We aim to predict the likelihood of hotel booking cancellations using customer behavior and reservation features.")

**Dataset Used:**  
Briefly mention the dataset source and what it contains.

**Why this problem matters:**  
Explain why this problem is interesting or valuable to solve.

---

## 🧹 Data Preparation

We performed the following data cleaning steps:

- Removed missing values / imputed where necessary
- Dropped irrelevant columns (e.g., booking ID, reservation status date)
- Encoded categorical variables using LabelEncoder / OneHotEncoder
- Handled class imbalance using [e.g., resampling, class weights]
- Selected top 5 features based on correlation to satisfy variable constraint

---

## 📊 Exploratory Data Analysis (EDA)

Here are some insights we derived from the dataset:

- Insight 1: e.g., "Bookings with children are more likely to get cancelled."
- Insight 2: e.g., "Lead time is positively correlated with cancellations."
- Insight 3: e.g., "Certain countries have higher cancellation rates."

We used:
- Heatmaps
- Histograms
- Correlation matrices
- Groupby summaries

> 🖼️ You can include some key EDA plots in a `plots/` folder or paste them into this README if small enough.

---

## 🤖 Machine Learning Approach

**Model Used:**  
We implemented and evaluated the following models:
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier (optional)

**Final Model:**  
The best performing model was: `RandomForestClassifier` with:
- Accuracy: `XX.X%`
- F1 Score: `X.XX`
- Confusion Matrix, Classification Report shown in `model_evaluation.ipynb`

**Why this model:**  
Explain why it was chosen (e.g., handles non-linearity, performs well on small feature sets, etc.)

**Learning Beyond the Course:**  
Mention what new thing you explored — e.g.,:
- Tried `class_weight='balanced'`
- Used `plot_tree()` to visualize tree structures
- Explored `XGBoost` or `GridSearchCV` for optimization

---

## 📈 Results & Insights

**Key Outcomes:**
- The model can predict cancellations with up to XX% accuracy.
- Lead time, deposit type, and booking changes were top predictors.

**Recommendations:**
- Hotels may reduce cancellations by limiting long lead-time bookings.
- Certain user profiles may benefit from targeted engagement.

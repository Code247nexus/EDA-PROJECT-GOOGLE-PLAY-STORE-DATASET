# 📱 Google Play Store App Analysis & Feature Engineering

This project focuses on **Exploratory Data Analysis (EDA)** and basic **feature engineering** on a dataset of over 10,000 Android apps published on the Google Play Store.

> 📌 **Version 1: EDA & Feature Engineering only**  
> 🔧 *Upcoming in Version 2: ML model to predict app popularity based on app metadata.*

---

## 📊 Objective

- Identify the **most popular app categories**
- Find the app with the **highest number of installs**, **largest size**, and **most reviews**
- Understand the distribution of **content ratings**, **free vs paid apps**, and **app pricing**
- Perform feature engineering (cleaning app size, price, installs for modeling)

---

## 📁 Dataset

- Source: [Kaggle Google Play Store Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- Rows: ~10,000 apps  
- Columns: 13 (App Name, Category, Rating, Reviews, Size, Installs, etc.)

---

## 🧼 EDA & Feature Engineering Summary

- Cleaned and converted:
  - App Size (e.g., 12M → float MB)
  - Installs (e.g., 1,000,000+ → int)
  - Price (e.g., $4.99 → float)
- One-hot/frequency encoded features like `Content Rating`, `Type`
- Created insights through visualizations:
  - Distribution of app ratings and installs
  - Top categories by install count
  - Free vs Paid app trends

---

## 📈 Sample Visuals

*(Replace these with actual image links if you export them)*

- ![Top Categories by Install Count](assets/top_categories.png)
- ![App Rating Distribution](assets/rating_dist.png)

---

## 🚀 Next Steps (v2 Plan)

- Train a machine learning model (e.g., Random Forest) to:
  - Predict whether an app will be “Popular” (e.g., > 1 million installs)
  - Use features like category, type, size, price, and rating
- Add performance metrics & business interpretations

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- google colab Notebook

---

## 📌 Author

**Aditya Jha**  
Aspiring Data Scientist | AIML Student  
[LinkedIn](www.linkedin.com/in/adityajha49) | [GitHub](https://github.com/Code247nexus/)

---

## 📂 License

This project is open-source under the [MIT License](LICENSE).

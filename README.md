# 🎬 Predicting Movie Ratings with Machine Learning

This project explores and models user movie ratings using the [MovieLens dataset](https://grouplens.org/datasets/movielens/). The aim is to build a multi-linear regression model that predicts movie ratings based on features like title, genres, release year, and timestamp.

---

## 📌 Objectives

- Analyze the MovieLens dataset using Python
- Build a regression-based recommender system
- Apply feature engineering to improve model accuracy
- Evaluate model performance using RMSE

---

## 📊 Key Steps

1. **Data Exploration** – Checked nulls, duplicates, and data types
2. **Data Visualization** – Trends in movie releases, genres, ratings
3. **Feature Engineering** – Title year extraction, genre encoding, timestamp conversion
4. **Model Building** – Linear regression with train/test/validation split
5. **Model Evaluation** – RMSE used to assess accuracy

---

## ⚙️ Tools & Technologies

- Python, Jupyter Notebook
- Pandas, Matplotlib, Seaborn
- Scikit-learn (LinearRegression, train_test_split)
- NumPy

---

## 📈 Results

| Metric                | RMSE     |
|-----------------------|----------|
| Cross-validation      | 0.762    |
| Internal test set     | 0.864    |
| Validation set        | 0.807    |

The model performed well on unseen data and shows good generalization. Feature engineering (like extracting year from title/timestamp) significantly improved performance.

---

## 📄 Files in This Repo

| File                          | Description                                |
|-------------------------------|--------------------------------------------|
| `MovieLens_Analysis.ipynb`    | Full notebook with analysis and modeling   |
| `report/assignment_summary.pdf` | Summary of methods, results, and discussion |
| `assets/visuals/`             | Charts extracted from notebook             |

---

## 🔮 Future Improvements

- Try TF-IDF on movie titles
- Add user demographics or cast/director features
- Compare with tree-based or ensemble models

---

## 👩🏽‍💻 Author

**Chipo Jokonya**  
MSc Applied Data Science  
[GitHub](https://github.com/chipoj) | [LinkedIn](https://linkedin.com/in/your-profile)

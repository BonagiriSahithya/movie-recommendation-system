
````markdown
# 🎬 Movie Recommendation System

This project is a **content-based movie recommendation system** built using Python. It suggests movies similar to a selected one based on their descriptions, genres, keywords, cast, and more.

---

## 📌 Features

- Recommend similar movies using content similarity
- Based on metadata like:
  - **Overview**
  - **Genres**
  - **Keywords**
  - **Cast & Crew**
- Simple and easy-to-understand implementation
- Great for learning **machine learning**, **NLP**, and **vectorization techniques**

---

## 🔍 How It Works

1. **Data Preprocessing**
   - Combines relevant metadata columns from the dataset
   - Cleans and tokenizes text for better representation

2. **Vectorization**
   - Uses `CountVectorizer` to convert text into numerical feature vectors

3. **Similarity Calculation**
   - Computes **cosine similarity** between all movie vectors

4. **Recommendation Function**
   - Accepts a movie name as input
   - Returns top 5 most similar movies

---

## 📁 Files Included

- `movie-recommendation.ipynb` – Jupyter Notebook with full implementation
- `movies.csv` – Dataset containing movie metadata
- `README.md` – Project documentation

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/BonagiriSahithya/movie-recommendation-system.git
cd movie-recommendation-system
````

### 2. Install Dependencies

Make sure you have Python installed. Then:

```bash
pip install pandas numpy scikit-learn
```

### 3. Run the Notebook

Launch the notebook in Jupyter:

```bash
jupyter notebook movie-recommendation.ipynb
```

---

## 💡 Example Output

If you input:
`Avatar`
The system might recommend:

* Guardians of the Galaxy
* Star Trek Into Darkness
* John Carter
* Prometheus
* The Fifth Element

---

## 📚 Concepts Used

* Content-Based Filtering
* Bag of Words (BoW) Vectorization
* Cosine Similarity
* Feature Engineering with Text Data

---

## 🙋‍♀️ Author

👤 [Bonagiri Sahithya](https://github.com/BonagiriSahithya)

---

## ⭐️ Show Your Support

If you like this project, consider giving it a ⭐️ on GitHub!

````

---

### ✅ How to Add This

1. Save the above content in your `README.md` file.
2. Then commit and push it:

```bash
git add README.md
git commit -m "Add beautifully formatted project README"
git push
````



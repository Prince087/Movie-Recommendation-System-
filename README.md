# 🎬 Movie Recommendation System (Content-Based)

This is a content-based movie recommendation system built using Python and Machine Learning. It recommends movies based on similarity of genres, keywords, cast, crew, and overview using cosine similarity.

---

## 🚀 Features
- Case-insensitive movie search
- Recommends top 5 similar movies
- Uses TMDB 5000 dataset
- Fast and accurate cosine similarity model

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📂 Project Structure
movie-recommendation-system/
app.py
tmdb_5000_movies.csv
tmdb_5000_credits.csv
requirements.txt
README.md
## 📁 Dataset Download

Due to GitHub file size limits, the dataset is not included in this repository.

Download it from here:
👉 https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download

After downloading, place both files inside the project folder.

---

▶️ How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/Prince087/Movie-Recommendation-System-.git

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Program
python app.py

🧠 How It Works

-Text features are extracted using CountVectorizer

-Cosine similarity is calculated between movie vectors

-Top 5 similar movies are recommended

📌 Sample Output
🎬 Top 5 Recommendations for 'Avatar':
✅ John Carter
✅ Guardians of the Galaxy
✅ The Avengers
✅ Man of Steel
✅ Titan A.E.

👨‍💻 Author

Prince Kumar
B.Tech Student | Machine Learning Enthusiast

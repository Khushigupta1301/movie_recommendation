# 🎬 Movie Recommendation System

A Machine Learning-based Movie Recommendation System that suggests similar movies based on their genres, cast, director, keywords, and overview using **Content-Based Filtering**. The system analyzes movie features and recommends movies that are most similar to the user's selected movie.

---

## 📌 Project Overview

The Movie Recommendation System helps users discover movies similar to the one they like. It uses Natural Language Processing (NLP) techniques to convert movie information into numerical vectors and calculates similarity using **Cosine Similarity**.

This project demonstrates data preprocessing, feature engineering, text vectorization, and recommendation algorithms using Python and Scikit-learn.

---

## 🚀 Features

- Recommend similar movies based on content
- Uses genres, cast, director, keywords, and movie overview
- Implements Content-Based Filtering
- Fast recommendation using Cosine Similarity
- Built using Python in Google Colab
- Beginner-friendly and easy to understand

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- CountVectorizer
- Cosine Similarity

---

## 📂 Dataset

This project uses the **TMDB Movie Metadata Dataset**.

Files used:
- `movies.csv`
- `credits.csv`

Dataset Source:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## ⚙️ How It Works

1. Load the movie and credits datasets.
2. Merge both datasets using the movie title.
3. Select useful features such as:
   - Overview
   - Genres
   - Keywords
   - Cast
   - Director
4. Clean and preprocess the data.
5. Create a combined "tags" feature.
6. Convert text into vectors using CountVectorizer.
7. Calculate movie similarity using Cosine Similarity.
8. Recommend the top 5 most similar movies.

---

## 📁 Project Structure

```
Movie-Recommendation-System/
│
├── Movie_Recommendation_System.ipynb
├── movies.csv
├── credits.csv
├── README.md
├── requirements.txt
├── movies.pkl
├── similarity.pkl
└── screenshots/
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie-Recommendation-System.git
```

Move into the project directory:

```bash
cd Movie-Recommendation-System
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook or open the project in Google Colab.

---

## 💻 Example

Input:

```
Avatar
```

Output:

```
John Carter
Titan A.E.
Guardians of the Galaxy
Aliens vs Predator
Star Trek Into Darkness
```

---

## 📊 Machine Learning Techniques Used

- Content-Based Filtering
- Natural Language Processing (NLP)
- Feature Engineering
- Count Vectorization
- Cosine Similarity

---

## 📈 Future Improvements

- Build an interactive web application using Streamlit.
- Add movie posters using the TMDB API.
- Implement Collaborative Filtering.
- Improve recommendations using TF-IDF Vectorizer.
- Deploy the application online.
- Add search suggestions and autocomplete.

---

## 📸 Screenshots

Add screenshots of your notebook or application here.

Example:

```
screenshots/
    home.png
    recommendations.png
```

---

## 📄 Requirements

```
numpy
pandas
scikit-learn
nltk
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📜 License

This project is intended for educational and learning purposes.

---

## 👩‍💻 Author

**Khushi Gupta**

GitHub: https://github.com/your-username

LinkedIn: https://www.linkedin.com/in/your-linkedin-profile/

---

⭐ If you found this project useful, don't forget to star the repository!

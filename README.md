<h1 align="center">🎬 Movie Recommendation using Machine Learning</h1>

<p align="center">
	<em><code>A content-based and collaborative filtering Movie Recommendation System using Python and Jupyter Notebook.</code></em>
</p>

<p align="center">
	<img src="https://img.shields.io/github/license/rishabh010105/Movie-Recommendation?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/rishabh010105/Movie-Recommendation?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/rishabh010105/Movie-Recommendation?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/rishabh010105/Movie-Recommendation?style=default&color=0080ff" alt="repo-language-count">
</p>

---

## 📌 Table of Contents

- [📖 Introduction](#-introduction)
- [🎯 Problem Statement](#-problem-statement)
- [🏆 Objectives](#-objectives)
- [📊 Dataset Description](#-dataset-description)
  - [✅ Data Preprocessing](#-data-preprocessing)
- [🏗️ Methodology](#️-methodology)
  - [🔹 Models Used](#-models-used)
  - [🔹 Recommendation Flow](#-recommendation-flow)
- [🚀 Results](#-results)
- [🔮 Future Work](#-future-work)
- [👥 Contributors](#-contributors)
- [📝 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 📖 Introduction

Movie recommendation systems are essential in helping users discover content they'll enjoy. This project uses **content-based filtering** and **text similarity** techniques to build a smart movie recommender. With Python and Jupyter Notebook, we generate accurate suggestions based on user input.

---

## 🎯 Problem Statement

With a vast amount of content available, users often struggle to decide what to watch. Manual exploration is inefficient and subjective. Our goal is to:

- Build a system that recommends movies based on **metadata similarity**.  
- Utilize **text feature extraction** and **vector similarity** methods.  
- Deliver an easy-to-use, notebook-based interface for testing.

---

## 🏆 Objectives

- Combine and clean movie metadata.  
- Generate a **tag feature** for each movie.  
- Apply **TF-IDF vectorization** for text feature engineering.  
- Use **cosine similarity** to find similar movies.  
- Create a function that outputs top-N recommendations.

---

## 📊 Dataset Description

The dataset includes essential movie attributes:

- Titles, Genres, Cast, Crew, Keywords, Overview, etc.

These are merged and cleaned to create a unified movie metadata dataset.

### ✅ Data Preprocessing

- Merge multiple CSV files (credits, movies, keywords).  
- Generate custom `tags` combining important text columns.  
- Apply **lowercasing**, **punctuation removal**, and **stemming**.  
- Vectorize text using **TF-IDF** for similarity comparison.

---

## 🏗️ Methodology

### 🔹 Models Used

- **TF-IDF Vectorizer** – to convert tags into numeric features.  
- **Cosine Similarity** – to compute movie-to-movie similarity.  
- *(Optional)* **CountVectorizer** and **SVD (planned)** for collaborative filtering in future versions.

### 🔹 Recommendation Flow

1. User inputs a movie title.  
2. The system fetches the index and computes similarity scores.  
3. Top-N most similar movies are returned based on cosine similarity.  
4. Results displayed interactively via Jupyter Notebook.

---

## 🚀 Results

- ✅ Successfully recommends relevant movies for popular inputs.  
- ⚙️ System is modular and easy to expand (e.g., with collaborative filtering).  
- 📈 TF-IDF proved more effective than CountVectorizer for textual features.  

---

## 🔮 Future Work

- Integrate **SVD** for collaborative filtering.  
- Build a **Flask or Streamlit** web app for deployment.  
- Add **movie posters and trailers** using TMDB API.  
- Incorporate **user feedback loop** for smarter learning.

---

## 👥 Contributors

- **Rishabh Jain** – Developer & Maintainer  
- 💬 [Join Discussions](https://github.com/rishabh010105/Movie-Recommendation/discussions)  
- 🐛 [Report Issues](https://github.com/rishabh010105/Movie-Recommendation/issues)

---

## 📝 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/)

---

## 🙏 Acknowledgments

- [Bharat Intern](https://bharatintern.live/) – Internship support  
- [Kaggle](https://www.kaggle.com) – Dataset source  
- [scikit-learn](https://scikit-learn.org) – ML tools  
- Open-source tutorials and communities


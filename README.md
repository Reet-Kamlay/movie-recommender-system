# 🎬 Movie Recommender System (Web Interface)

This repository contains a **Flask-based web application** built on top of a content-based movie recommendation engine. It allows users to input a movie title and receive a list of similar movies based on metadata such as genres, keywords, cast, and crew.

---

## 🧠 Project Overview

The recommendation logic is derived from vector similarity (cosine similarity) between movie metadata "tags". The backend loads preprocessed data and returns relevant results via a simple web UI.

This project complements the [movie-recommend](https://github.com/Reet-Kamlay/movie-recommend) notebook-based system by adding a usable web interface.

---

## 📁 Project Structure

```
movie-recommender-system/
│
├── app.py                   # Flask backend
├── templates/
│   └── index.html           # Web UI for user input and displaying results
├── static/
│   └── style.css            # Optional styling
├── similarity.pkl           # Precomputed similarity matrix
├── movies_dict.pkl          # Processed movie metadata dictionary
├── requirements.txt         # Python dependencies
└── README.md
```

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Reet-Kamlay/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask application**
   ```bash
   python app.py
   ```

4. **Open your browser and go to**
   ```
   http://127.0.0.1:5000/
   ```

---

## ✅ Features

- Dropdown input with movie titles
- Content-based recommendations using cosine similarity
- Preprocessed `.pkl` files for fast loading
- Lightweight and easy to deploy

---

## 🛠️ Tech Stack

- Python
- Flask
- HTML/CSS (Jinja templating)
- Pandas
- Scikit-learn
- Pickle

---

## 🗂 Related Repositories

- 📦 [movie-recommend](https://github.com/Reet-Kamlay/movie-recommend): Jupyter Notebook-based backend system for content-based movie recommendations.

---

## 👤 Author

**Reet Kamlay**  
[GitHub](https://github.com/Reet-Kamlay) • [LinkedIn](https://www.linkedin.com/in/reetkamlay/)

---

⭐ If you found this useful, please consider starring the repo!

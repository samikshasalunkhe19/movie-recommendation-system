# 🎬 Movie Recommendation System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-Enabled-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</div>

---

## 📌 Overview

The **Movie Recommendation System** is a Machine Learning project that recommends movies based on content similarity.  
This system uses **Natural Language Processing (NLP)** techniques and **Content-Based Filtering** to suggest movies similar to a user's selected movie.

The recommendation engine analyzes movie descriptions and calculates similarity scores using **TF-IDF Vectorization** and **Cosine Similarity**.

---

## 🚀 Features

✔️ Content-Based Movie Recommendation  
✔️ NLP-Based Text Processing  
✔️ TF-IDF Vectorization  
✔️ Cosine Similarity Matching  
✔️ Fast Recommendation Generation  
✔️ Beginner-Friendly ML Project  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Scikit-learn | Machine Learning |
| NLP | Text Processing |
| Jupyter Notebook | Development Environment |

---

## 📂 Dataset

This project uses the **TMDB 5000 Movie Dataset** containing:

- Movie Titles
- Movie Overviews
- Genres
- Ratings
- Keywords
- Cast Information

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection
- Imported movie dataset using Pandas.

### 2️⃣ Data Preprocessing
- Removed null values
- Selected important features
- Cleaned textual data

### 3️⃣ Feature Extraction
Used **TF-IDF Vectorizer** to convert textual movie descriptions into numerical vectors.

```python
from sklearn.feature_extraction.text import TfidfVectorizer
```

---

### 4️⃣ Similarity Calculation
Calculated similarity scores between movies using **Cosine Similarity**.

```python
from sklearn.metrics.pairwise import cosine_similarity
```

---

### 5️⃣ Recommendation Generation
The system recommends the top similar movies based on similarity scores.

---

## 📸 Example

### Input

```python
recommend("Inception")
```

### Output

```python
[
    'Interstellar',
    'The Prestige',
    'Shutter Island',
    'Memento',
    'The Dark Knight'
]
```

---

## 📊 Machine Learning Concepts Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Content-Based Filtering
- Cosine Similarity
- Text Feature Engineering

---

## 📁 Project Structure

```bash
Movie-Recommendation-System/
│
├── movie_recommendation.ipynb
├── README.md
├── dataset/
│   └── movies.csv
│
└── requirements.txt
```

---

## ▶️ Installation & Setup

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

---

### Step 2: Navigate to Project Directory

```bash
cd movie-recommendation-system
```

---

### Step 3: Install Dependencies

```bash
pip install pandas numpy scikit-learn
```

---

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
movie_recommendation.ipynb
```

---

## 📈 Future Enhancements

- 🎯 Build Streamlit Web Application
- 🎯 Add Movie Posters
- 🎯 Improve Recommendation Accuracy
- 🎯 Implement Collaborative Filtering
- 🎯 Deploy Project on Cloud Platforms

---

## 🤝 Contributing

Contributions are welcome!

If you would like to contribute:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request


---

## 👩‍💻 Author

### **Samiksha Salunkhe**
Machine Learning & Data Science Enthusiast 🚀
🔗 GitHub: https://github.com/samikshasalunkhe19
💼 LinkedIn:www.linkedin.com/in/samiksha-salunkhe-03b416332

---

<div align="center">

⭐ If you like this project, don't forget to star the repository!

</div>

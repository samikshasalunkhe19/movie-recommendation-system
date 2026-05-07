# 🎬 Movie Recommendation System

<div align="center">

<img src="https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?q=80&w=1200&auto=format&fit=crop" width="100%" alt="Movie Recommendation Banner">

<br><br>

### Intelligent Movie Recommendation Engine using Machine Learning & NLP

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-brightgreen?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

# 📌 Project Overview

The **Movie Recommendation System** is a Machine Learning-based application designed to recommend movies similar to a user's selected movie.  
The project utilizes **Natural Language Processing (NLP)** and **Content-Based Filtering** techniques to analyze movie descriptions and identify similarities between movies.

By applying **TF-IDF Vectorization** and **Cosine Similarity**, the system generates personalized and relevant movie recommendations efficiently.

---

# 🚀 Key Features

- Content-Based Movie Recommendation
- NLP-Based Text Feature Extraction
- TF-IDF Vectorization
- Cosine Similarity Matching
- Fast Recommendation Generation
- Scalable Recommendation Logic
- Beginner-Friendly Machine Learning Project

---

# 🛠️ Technologies Used

| Technology | Description |
|---|---|
| Python | Core Programming Language |
| Pandas | Data Manipulation & Analysis |
| NumPy | Numerical Computation |
| Scikit-learn | Machine Learning Library |
| NLP | Text Processing Techniques |
| Jupyter Notebook | Development Environment |

---

# 📂 Dataset Information

The project uses the **TMDB 5000 Movie Dataset** containing movie-related metadata such as:

- Movie Titles
- Overviews
- Genres
- Keywords
- Cast Information
- Ratings

The dataset is used to analyze textual content and generate similarity scores between movies.

---

# ⚙️ Methodology

## 1. Data Collection
The movie dataset is imported and loaded using the Pandas library.

---

## 2. Data Preprocessing
Data preprocessing steps include:

- Handling missing values
- Selecting relevant features
- Cleaning textual data
- Preparing the dataset for vectorization

---

## 3. Feature Extraction
Textual movie descriptions are converted into numerical vectors using **TF-IDF Vectorization**.

```python
from sklearn.feature_extraction.text import TfidfVectorizer
```

---

## 4. Similarity Computation
The similarity between movies is calculated using **Cosine Similarity**.

```python
from sklearn.metrics.pairwise import cosine_similarity
```

---

## 5. Recommendation Generation
Based on similarity scores, the system recommends the most relevant movies similar to the selected movie.

---

# 📸 Sample Recommendation

## Input

```python
recommend("Inception")
```

## Output

```python
[
    "Interstellar",
    "The Prestige",
    "Shutter Island",
    "Memento",
    "The Dark Knight"
]
```

---

# 📊 Machine Learning Concepts Applied

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Content-Based Filtering
- Cosine Similarity
- Text Feature Engineering

---

# 📁 Project Structure

```bash
Movie-Recommendation-System/
│
├── README.md
├── movie_recommendation.ipynb
├── dataset/
│   └── movies.csv
│
└── requirements.txt
```

---

# ▶️ Installation & Execution

## Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

---

## Navigate to Project Directory

```bash
cd movie-recommendation-system
```

---

## Install Required Dependencies

```bash
pip install pandas numpy scikit-learn
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file:

```bash
movie_recommendation.ipynb
```

---

# 📈 Future Enhancements

- Develop Interactive Web Application using Streamlit
- Integrate Movie Posters & Metadata
- Implement Collaborative Filtering Techniques
- Improve Recommendation Accuracy
- Deploy the Application on Cloud Platforms

---


## 👩‍💻 Author

### **Samiksha Salunkhe**
Machine Learning & Data Science Enthusiast 🚀

- 🔗 GitHub: https://github.com/samikshasalunkhe19
- 💼 LinkedIn:www.linkedin.com/in/samiksha-salunkhe-03b416332

---

<div align="center">

⭐ If you like this project, don't forget to star the repository!

</div>

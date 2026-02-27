# 🎬 Movie Recommendation System using Python

A content-based Movie Recommendation System built with **Python, Machine Learning, and Streamlit**. This app recommends similar movies based on the selected movie and displays their posters using the TMDB API.

---
## 🚀 Features

* 🔍 Search for any movie
* 🎯 Get top 5 similar movie recommendations
* 🖼️ Display movie posters using TMDB API
* 💻 Interactive web app using Streamlit
* ⚡ Fast and simple UI
* 
---

## 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Streamlit
* Requests
* Joblib / Pickle
* TMDB API

---

## 📂 Project Structure

Movie-Recommendation-System
│
├── movies.py              # Main Streamlit app
├── movie.pkl              # Movie dataset
├── similarity.pkl        # Similarity matrix
├── requirements.txt      # Required libraries
└── README.md             # Project documentation

---

## ⚙️ Installation

### Step 1: Install dependencies

  ---> pip install streamlit pandas scikit-learn requests joblib

### Step 2: Get TMDB API key

1. Go to https://www.themoviedb.org/
2. Create account
3. Go to Settings → API
4. Generate API key
5. Replace in code:

```python
api_key = "YOUR_API_KEY"
```
---

## ▶️ Run the application
  ---> streamlit run movies.py

---

## 🧠 How it works

* Uses content-based filtering
* Calculates cosine similarity between movies
* Finds top 5 similar movies
* Fetches posters using TMDB API
* Displays recommendations in Streamlit UI

---

## 📸 Output Example

Selected Movie: Avatar

Recommended Movies:
• John Carter
• Guardians of the Galaxy
• Avengers
• Star Wars
• Interstellar
(with posters)

---

## 🎯 Learning Outcomes

* Machine Learning basics
* Recommendation systems
* API integration
* Streamlit web app development
* Real-world project experience
  
---

## 👨‍💻 Author

**Nirankar Singh**
BTech Data Science Student
Python Developer

---

## 📌 Future Improvements

* Add user-based recommendation
* Deploy on cloud (Streamlit Cloud / AWS)
* Add movie details (rating, overview)
* Add search autocomplete
* 
---
---


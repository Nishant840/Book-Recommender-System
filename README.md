# 📚 Book Recommender System

A web-based book recommendation system that helps users discover books based on popularity and personalized suggestions. Built with **Flask**, this project combines **popularity-based recommendations** and **collaborative filtering** to provide users with the best book recommendations.

[🔗 Try it live!](https://book-recommender-system-ktwt.onrender.com/)

---

## Features

- **Popularity-Based Recommender**: Shows the top 50 books based on ratings and popularity.  
- **Collaborative Filtering**: Personalized book recommendations based on user preferences and similar users.  
- **Interactive Web Interface**: Users can easily search and get recommendations through a clean and simple UI.  

---

## Demo

Here’s how the app looks:

---

## Technologies Used

- **Flask** – Python web framework for building the web application  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Scikit-Learn** – Collaborative filtering and similarity calculations  
- **HTML/CSS** – Frontend for the web interface  

---

## How It Works

1. **Popularity-Based Recommendations**:  
   The system first displays the top 50 books based on ratings and the number of users who rated them.

2. **Collaborative Filtering**:  
   Based on the user’s selected book, the system finds similar users and recommends books they liked. This ensures personalized and relevant suggestions.

## Installation (For Local Setup)

1. Clone the repository:
```bash
   git clone https://github.com/Nishant840/Book-Recommender-System.git
   cd Book-Recommender-System

2. Create a virtual environment:

python -m venv venv

3. Activate the virtual environment:

# On Linux / macOS
source venv/bin/activate

# On Windows
venv\Scripts\activate

4. Install dependencies:

pip install -r requirements.txt

5. Run the app:

python app.py

6. Open your browser at:

http://127.0.0.1:5000/


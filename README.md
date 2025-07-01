# 📚 BiblioSuggest – Book Recommendation System

## Overview
BiblioSuggest is a smart recommendation engine designed to help users find books they’ll love. It allows users to:
- Discover the top 50 most popular books.
- Get similar book recommendations based on user input.
- Explore random book suggestions.

Built with collaborative filtering and popularity-based models, the system uses a large dataset of 271,360 books and 278,858 user ratings to ensure meaningful and accurate recommendations.

## 🔧 Features
- Top-N recommendations based on popularity.
- Similar book suggestions using collaborative filtering.
- Random book generator.
- Flask web interface for easy interaction.

## 🚀 Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, Surprise (for collaborative filtering)
- Google Colab (development)
- Flask (deployment)

## 📊 Dataset
Used a Kaggle book dataset with:
- 271,360 books
- 278,858 user ratings

## 👥 Team
Led by Shivani Prasad with a team of 4 developers.

## 📁 How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Run Flask app: `python app.py`
4. Visit: `http://127.0.0.1:5000`

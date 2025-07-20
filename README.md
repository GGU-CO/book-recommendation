# 📚 Book Recommendation System

A personalized recommendation engine built using Python and Flask that suggests books based on user input using similarity metrics such as Cosine Similarity, Jaccard Index, and Simple Matching Coefficient (SMC).

## 🔍 Project Overview

This project aims to enhance the book discovery experience by analyzing user preferences and suggesting relevant titles using similarity-based filtering techniques. With a clean and responsive Flask web interface, users can easily search and get recommendations based on their favorite books.

## 🎯 Key Features

- 📘 Recommends books using:
  - Cosine Similarity
  - Jaccard Similarity
  - Simple Matching Coefficient (SMC)
- 🧮 Analyzed over 10,000 books and 5,000+ user ratings from a Kaggle dataset
- 🧪 Achieved **99.5% accuracy** with SMC in controlled test environment
- 🌐 Deployed using Flask with a user-friendly interface for real-time suggestions
- 📊 Cleaned and normalized data using Pandas and NumPy for optimal model performance

## 🛠️ Technologies Used

- **Python** (data processing and backend logic)
- **Flask** (web framework for deployment)
- **Pandas & NumPy** (data manipulation and vectorization)
- **scikit-learn** (similarity metrics and ML utilities)
- **HTML/CSS** (UI development)

## 📁 Dataset

- Source: [Kaggle Book Dataset]
- Includes:
  - Book titles, authors, and ISBNs
  - User ratings matrix
  - Preprocessed for noise removal and normalization

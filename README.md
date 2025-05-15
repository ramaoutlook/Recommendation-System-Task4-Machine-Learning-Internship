# Recommendation-System-Task4-Machine-Learning-Internship
Book Recommendation System project developed with Collaborative Filtering Technique with Pyhton and Flask

# Task 3 Image-Classification-with-CNN-Keras-Tensorflow-CIFER-10

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : BOYAPATI RAMA KRISHNA

*INTERN ID* : CT04DK494

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

# 📚 Book Recommendation System

This project is a Book Recommendation System developed as part of a Machine Learning internship task. It uses **Collaborative Filtering** to recommend books based on user preferences. The system is built using Python and deployed via a **Flask web interface** to provide interactive, real-time recommendations.

The dataset used for this project is the [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset) from Kaggle. It contains information about books, users, and their ratings. The project follows a content-rich and practical approach inspired by a YouTube tutorial, with major modifications and extensions tailored to this internship project.

## 🔍 Overview

The goal is to assist readers in discovering new books that match their interests. By applying **Collaborative Filtering**, we identify patterns from user ratings to suggest books that similar users have enjoyed. This method enhances personalization and improves user engagement.

## 🛠️ Techniques Used

- **Data Cleaning & Preprocessing**: Merged and cleaned `Books.csv`, `Users.csv`, and `Ratings.csv`.
- **Collaborative Filtering**: Built a user-item interaction matrix using book ratings and applied cosine similarity to generate recommendations.
- **Flask Web App**: Created a responsive interface to allow users to search for a book and receive suggestions.
- **Deployment Ready**: Project is structured with `Procfile`, `requirements.txt`, and model files for Heroku deployment.

## 📂 Dataset Information

Dataset from Kaggle:
- `Books.csv`: Metadata like title, author, year, publisher.
- `Users.csv`: User demographic information (location, age).
- `Ratings.csv`: Ratings provided by users for different books.

Dataset Link: [Book Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

## 🚀 Output
![Image](https://github.com/user-attachments/assets/d405804e-e2a9-4af1-bea6-7b09e8f22ac7)
![Image](https://github.com/user-attachments/assets/ea910e38-7e21-4913-9623-6120483793fe)
![Image](https://github.com/user-attachments/assets/960f27a6-d2af-4414-b7e7-e1c1d905bc7b)

## 🚀 Features

- Personalized book recommendations based on collaborative filtering
- Searchable and interactive Flask-based UI
- Clean and production-ready code for model training and web deployment
- Google Colab notebook available for code inspection and experimentation

## 🧠 Future Enhancements

- Include user-based collaborative filtering in addition to item-based
- Add content-based filtering using book metadata
- Incorporate user login and history tracking in the web app
- Deploy to cloud platforms like Heroku or Render for public access

---

This project demonstrates how collaborative filtering can be effectively applied to build recommendation engines, offering a practical blend of machine learning, data engineering, and web development.

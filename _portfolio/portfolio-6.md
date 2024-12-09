
---
title: "End-To-End Book Recommender System"
excerpt: "This project is about building a web app that recommends books to users. The system uses two main methods: popularity-based filtering to suggest widely loved books, and collaborative filtering to provide personalized recommendations based on user preferences.<br/><img src=''>"
collection: portfolio
---

## Images of UI
![UI Image 1](https://github.com/23MD/Book-Recommendation-System/blob/08a062d932150ca6047be01201a555f9cbd74293/Book-Recommendation-System-1.png)
![UI Image 2](https://github.com/23MD/Book-Recommendation-System/blob/08a062d932150ca6047be01201a555f9cbd74293/Book-Recommendation-System-2.png)

Visit the website [here](https://book-recommendation-system-9ruh.onrender.com/).

## Description
The main goal of this project is to make it easier for users to find books they’ll enjoy by using two key techniques:

- **Popularity-Based Filtering**: This method suggests books that are popular among many readers. It’s especially useful for new users or those who don’t have much reading history on the platform.

- **Collaborative Filtering**: This method gives personalized recommendations by looking at what similar users have enjoyed. It helps tailor book suggestions to match each user's unique taste.

By combining these techniques, the recommender system offers both popular and personalized book recommendations, helping users find their next great read more quickly and easily.

## Dataset
### Dataset Source
[Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

### Dataset Information
The dataset includes three files:

- **Books Table**: Contains 8 columns and 271,360 rows.
  - `ISBN`: International Standard Book Number
  - `Book-Title`: Title of the book
  - `Book-Author`: Author's name
  - `Year-of-Publication`: Year the book was published
  - `Publisher`: Publisher's name
  - `Image-URL-S`, `Image-URL-M`, `Image-URL-L`: URLs for small, medium, and large images of the book cover

- **Ratings Table**: Contains 3 columns and 1,149,780 rows.
  - `User-ID`: Unique ID for each user
  - `ISBN`: International Standard Book Number
  - `Book-Rating`: Rating given by the user (1 to 10)

- **Users Table**: Contains 3 columns and 278,858 rows.
  - `User-ID`: Unique ID for each user
  - `Location`: User's location
  - `Age`: User's age

## Technology Stack
- **Programming Language**: Python
- **Web Framework**: Flask
- **Frontend**: Bootstrap
- **Development Environment**: Visual Studio Code, Jupyter Notebook

## Libraries Used
- **Flask**: Web framework
- **Pandas**: Data manipulation
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Pickle**: Model serialization
- **Logging**: Debugging

## Acknowledgment
Special thanks to [CampusX YouTube Channel](https://www.youtube.com/@campusx-official) for their insightful tutorials and guidance.

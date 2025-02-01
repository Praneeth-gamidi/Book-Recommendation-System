# Book-Recommendation-System

## Project Overview
This project is a **Book Recommendation System** that suggests similar books to users based on their preferences. The system utilizes **Euclidean distance** to measure similarity between books based on user ratings and book categories.

## Features
* Reads book, user, and rating data from Excel files.
* Prepares a feature matrix including categorical encoding for book genres.
* Constructs a **user-book rating matrix**.
* Uses **Euclidean distance** to compute book similarity.
* Generates personalized book recommendations based on a user's reading history and age group.

## Technologies Used
 **Python**
 **Pandas** for data handling
 **NumPy & Math** for calculations
 **OpenPyXL** for handling Excel files

## Dataset
The system processes three datasets:
1. `books.xlsx`: Contains book details (Book ID, Title, Category, Target Age Group, etc.).
2. `ratings.xlsx`: Stores user ratings (User ID, Book ID, Rating).
3. `users.xlsx`: Includes user details (User ID, Age, Preferences).

## Installation and Setup
### Prerequisites
Ensure you have **Python 3.x** installed along with the required libraries.

### Install Dependencies

pip install pandas openpyxl

### How to Run the Project
1. Place the dataset files (`books.xlsx`, `ratings.xlsx`, `users.xlsx`) in the project directory.
2. Run the Python script:
   
   python book_recommendation.py
   
3. Enter your **User ID**, **Book Title**, and **Number of Recommendations** when prompted.
4. The system will output a list of books similar to the entered title.

## Example Usage
```
Enter Your user ID: 102
Enter book title for which you need similar books: The Alchemist
Enter number of recommendations: 5

Books similar to 'The Alchemist' for user with ID 102:
['The Monk Who Sold His Ferrari', 'The Power of Now', 'Think and Grow Rich', 'Atomic Habits', 'Rich Dad Poor Dad']
```

## Future Improvements
* Implement **Collaborative Filtering** for better recommendations.
* Use **Cosine Similarity** instead of Euclidean distance.
* Improve performance with **matrix factorization techniques**.
* Build a web interface for a better user experience.




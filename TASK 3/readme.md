
🎬 Movie Recommendation System (Python)
📌 Project Description

This is a simple console-based Movie Recommendation System built using Python.
The program recommends movies based on:

User’s preferred genre
Minimum IMDb-style rating

It filters movies from a predefined list and displays the best-rated recommendations.

🚀 Features
Displays all available movie genres
Takes user input for genre and rating
Filters movies based on user preference
Sorts results by rating (highest first)
Beginner-friendly and easy to understand
🛠️ Technologies Used
Python
Core Python concepts:
Lists
Dictionaries
Loops
Conditional statements
Sorting with lambda
📂 Project Structure
movie-recommendation/
│
├── movie_recommendation.py
└── README.md
▶️ How to Run the Program
Step 1: Install Python

Make sure Python is installed on your system.

Check version:

python --version
Step 2: Run the Program
python movie_recommendation.py
🧑‍💻 How It Works
The program stores movie data in a list of dictionaries
It displays all available genres
The user enters:
Preferred genre
Minimum rating
The system:
Filters matching movies
Sorts them by rating (descending)
Recommended movies are displayed on screen
📥 Sample Input
Enter preferred genre: Sci-Fi
Enter minimum rating (0-10): 8.5
📤 Sample Output
Recommended Movies:

1. Interstellar (Genre: Sci-Fi, Rating: 9.0)
2. Inception (Genre: Sci-Fi, Rating: 8.8)
3. The Matrix (Genre: Sci-Fi, Rating: 8.7)
📌 Example Movie Data
{"title": "Interstellar", "genre": "Sci-Fi", "rating": 9.0}
🌱 Future Improvements
Add more movies (100+)
Allow multiple genre selection
Add year, director, language filters
Create GUI or Web App version
Store data using files or databases
🎓 Learning Outcome
Improved understanding of Python data structures
Hands-on experience with filtering and sorting logic
Basic recommendation system logic
📜 License

This project is created for learning and educational purposes.

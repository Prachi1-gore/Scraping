🧠 Project Title: Metacritic Top 1000 Movies Scraper

🎯 Overview
This Python project is designed to scrape information for the Top 1000 most popular movies from Metacritic's "Movies of All Time" list. It extracts each movie's title, director(s), and full cast using Python’s web scraping tools. The final product is an interactive tool that allows users to query this data in multiple ways and perform similarity analysis between directors.

🛠️ Features
✅ Scrapes titles, directors, and full cast lists from Metacritic.

✅ Builds a nested dictionary of movie data.

✅ Stores output in a clean CSV file.

✅ Interactive command-line interface with three modes:

Movie: Retrieve the director and full cast for a given movie title.

Director: Retrieve all movies by a director and their actor collaboration stats.

Comparison: Compare two directors using cosine similarity of actor collaboration vectors.

📂 Project Structure

├── Project_PrachiGore.ipynb          # Main Jupyter notebook containing the scraping and CLI logic
├── PrachiGore_movies.csv             # Output CSV file with movie, director, and cast data
└── Director_Analysis_Report.docx     # Summary of findings from comparing 5 selected directors

📌 Technologies Used
Python 3.x
Jupyter Notebook
Requests
BeautifulSoup
Pandas
Numpy
Math (for cosine similarity)

⚙️ How to Run
Clone or download the repository.
Install required packages:
pip install requests beautifulsoup4 pandas
Run the notebook: Project_PrachiGore.ipynb.

Follow the on-screen prompts to query by:
Movie name
Director name
Two directors for comparison

🧪 Example Usage
What do you want to check on Metacritic? (Please choose ‘movie’, ‘people’, or ‘comparison’)
> movie
What movie do you want to check?
> parasite

The director of the movie Parasite is Bong Joon-ho.
The cast includes: Song Kang-ho, Lee Sun-kyun, Cho Yeo-jeong, Choi Woo-shik, Park So-dam...

📈 Cosine Similarity Comparison
Given two directors, the program calculates how often they’ve worked with the same actors and returns a cosine similarity score, indicating how closely related their casting history is.

🧾 Final Report
The accompanying report summarizes personal insights after analyzing and comparing the careers of five notable directors from the scraped dataset.

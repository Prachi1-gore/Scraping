# Metacritic Top 1000 Movies Scraper

**Welcome to the Metacritic Top 1000 Movies Scraper repository! 🚀 This project demonstrates comprehensive web scraping capabilities and interactive data analysis for movie industry insights.**

## 🏗️ Data Architecture

The data architecture for this project follows a structured approach:

1. **Data Source**: Metacritic's "Movies of All Time" list - web scraping from live website data
2. **Data Extraction**: Python-based scraping using BeautifulSoup and Requests libraries
3. **Data Processing**: Cleaning and structuring scraped data into organized formats
4. **Data Storage**: CSV output with structured movie, director, and cast information
5. **Interactive Analysis**: Command-line interface for querying and analyzing the dataset

## 📖 Project Overview

This project involves:

1. **Web Scraping**: Automated extraction of movie data from Metacritic's top movies list
2. **Data Processing**: Cleaning and organizing scraped content into structured formats
3. **Interactive Querying**: Command-line interface for movie and director lookups
4. **Similarity Analysis**: Mathematical comparison of director collaboration patterns
5. **Data Visualization**: Insights and analysis through structured reporting

## 🚀 Project Requirements

### Web Scraping & Data Engineering

**Objective**
Develop a comprehensive web scraping solution to extract and analyze movie data from Metacritic, enabling interactive queries and director comparison analysis.

**Specifications**
* **Data Sources**: Scrape Top 1000 movies from Metacritic's "Movies of All Time" list
* **Data Extraction**: Extract movie titles, directors, and complete cast information
* **Data Quality**: Implement robust scraping with error handling and data validation
* **Storage**: Export clean, structured data to CSV format for analysis
* **Scope**: Focus on comprehensive data extraction with interactive analysis capabilities
* **Documentation**: Provide clear interface documentation and usage examples

### Interactive Data Analysis

**Objective**
Create an interactive command-line tool for querying movie data and performing advanced director similarity analysis using mathematical algorithms.

**These capabilities empower users with:**
* **Movie Lookup**: Instant access to director and cast information
* **Director Analysis**: Comprehensive filmography and collaboration insights
* **Similarity Comparison**: Mathematical analysis of director collaboration patterns

## 🎯 Key Features

### Web Scraping Capabilities
- **Automated Data Extraction**: Scrapes titles, directors, and full cast lists from Metacritic
- **Robust Error Handling**: Manages network issues and parsing errors gracefully
- **Data Validation**: Ensures data quality and consistency during extraction
- **Scalable Architecture**: Designed to handle large datasets efficiently

### Data Processing & Storage
- **Nested Dictionary Structure**: Organizes movie data in hierarchical format
- **CSV Export**: Clean, structured output for further analysis
- **Data Normalization**: Standardizes names and formats for consistency
- **Memory Efficient**: Optimized processing for large datasets

### Interactive Query System
- **Multi-Mode Interface**: Three distinct query modes for different use cases
- **Real-Time Lookup**: Instant search and retrieval of movie information
- **User-Friendly Design**: Intuitive command-line interface with clear prompts

### Advanced Analytics
- **Cosine Similarity Analysis**: Mathematical comparison of director collaboration patterns
- **Collaboration Statistics**: Quantitative analysis of actor-director relationships
- **Pattern Recognition**: Identifies similarities in casting choices between directors

## 📊 System Components

### 1. Web Scraping Engine
- **HTTP Request Management**: Efficient handling of web requests to Metacritic
- **HTML Parsing**: BeautifulSoup-based extraction of structured data
- **Data Extraction Logic**: Targeted scraping of movie titles, directors, and cast information

### 2. Data Processing Pipeline
- **Data Cleaning**: Standardization and normalization of scraped content
- **Structure Organization**: Building nested dictionaries for efficient data access
- **Quality Assurance**: Validation and error checking throughout the pipeline

### 3. Interactive Query Interface
- **Movie Mode**: Retrieve director and full cast for specific movie titles
- **Director Mode**: Access complete filmography and collaboration statistics
- **Comparison Mode**: Mathematical similarity analysis between directors

### 4. Similarity Analysis Engine
- **Vector Representation**: Converting director collaboration data into mathematical vectors
- **Cosine Similarity Calculation**: Measuring relationship strength between directors
- **Statistical Analysis**: Quantitative insights into collaboration patterns

## 🛠️ Technical Implementation

### Core Technologies
- **Python 3.x**: Primary programming language for scraping and analysis
- **Requests**: HTTP library for web scraping functionality
- **BeautifulSoup**: HTML parsing and data extraction
- **Pandas**: Data manipulation and CSV export
- **NumPy**: Numerical computations for similarity analysis
- **Math**: Mathematical operations for cosine similarity calculations

### Data Structures
- **Nested Dictionaries**: Hierarchical organization of movie data
- **Vector Representations**: Mathematical encoding of director collaboration patterns
- **CSV Format**: Structured tabular output for data persistence

### Key Algorithms
- **Web Scraping Logic**: Systematic extraction of movie information
- **Data Normalization**: Standardization of names and formats
- **Cosine Similarity**: Mathematical comparison of director collaboration vectors
- **Statistical Analysis**: Quantitative insights into filmography patterns

## 📂 Project Structure

```
├── Project_PrachiGore.ipynb          # Main Jupyter notebook with scraping and CLI logic
├── PrachiGore_movies.csv             # Output CSV file with movie, director, and cast data
├── Director_Analysis_Report.docx     # Summary of findings from director comparisons
└── README.md                         # Project documentation
```

## ⚙️ How to Run

### Prerequisites
```bash
pip install requests beautifulsoup4 pandas numpy
```

### Execution Steps
1. **Clone or download** the repository
2. **Install required packages** using the command above
3. **Run the notebook**: `Project_PrachiGore.ipynb`
4. **Follow on-screen prompts** to query by:
   - Movie name
   - Director name
   - Two directors for comparison

## 🧪 Example Usage

### Movie Query
```
What do you want to check on Metacritic? (Please choose 'movie', 'people', or 'comparison')
> movie

What movie do you want to check?
> parasite

The director of the movie Parasite is Bong Joon-ho.
The cast includes: Song Kang-ho, Lee Sun-kyun, Cho Yeo-jeong, Choi Woo-shik, Park So-dam...
```

### Director Analysis
```
What do you want to check on Metacritic? (Please choose 'movie', 'people', or 'comparison')
> people

What director do you want to check?
> christopher nolan

Director: Christopher Nolan
Movies: Inception, The Dark Knight, Interstellar, Dunkirk...
Collaboration Statistics: [Detailed actor collaboration analysis]
```

### Similarity Comparison
```
What do you want to check on Metacritic? (Please choose 'movie', 'people', or 'comparison')
> comparison

Enter first director: martin scorsese
Enter second director: quentin tarantino

Cosine Similarity Score: 0.234
Analysis: These directors show moderate similarity in their casting choices...
```

## 📈 Cosine Similarity Analysis

The similarity comparison feature calculates how often two directors have worked with the same actors, providing insights into:

- **Collaboration Patterns**: Quantitative analysis of shared casting choices
- **Industry Relationships**: Understanding connections between filmmakers
- **Casting Preferences**: Identifying similar artistic approaches through actor selections
- **Career Trajectories**: Comparing director evolution through collaboration data

## 📊 Business Value

### Data Science Applications
- **Pattern Recognition**: Identifying trends in movie industry collaborations
- **Predictive Analysis**: Understanding factors that influence casting decisions
- **Network Analysis**: Mapping relationships within the film industry
- **Market Research**: Insights into successful director-actor partnerships

### Technical Achievements
- **Scalable Web Scraping**: Robust extraction from complex web structures
- **Mathematical Analysis**: Implementation of similarity algorithms
- **Interactive Systems**: User-friendly command-line interfaces
- **Data Pipeline**: End-to-end processing from raw web data to analytical insights

## 🧾 Final Report

The accompanying Director Analysis Report provides comprehensive insights after analyzing and comparing five notable directors from the scraped dataset, including:

- **Collaboration Network Analysis**: Detailed examination of director-actor relationships
- **Career Pattern Recognition**: Identifying common themes in filmmaking approaches
- **Quantitative Insights**: Statistical analysis of collaboration frequencies
- **Industry Trends**: Broader patterns in movie industry collaborations

## 🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm Prachi Gore.

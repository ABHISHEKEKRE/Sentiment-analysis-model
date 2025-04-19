Personal Natural Language Processing Project: Article Analyzer
Introduction
Welcome to the Article Analyzer, an NLP-driven processing pipeline designed for sentiment analysis of articles. This project webscrapes articles, processes their linguistic features, and extracts sentiment metrics such as positivity and polarity scores, storing the results for further analysis.
Features

Web Scraping: Collects 100 article links from CSV files for analysis.
Sentiment Analysis Pipeline: Analyzes linguistic features, including positivity score, polarity score, and more.
Text Preprocessing: Implements tokenization, stopword removal, and stemming/lemmatization.
Data Storage: Saves processed features in CSV files and articles in 100 individual text files.
Feature Extraction: Extracts over 1,000+ feature records from 100 articles.

Technology Stack

Language: Python
Libraries:
BeautifulSoup (for web scraping)
NLTK (for natural language processing)
spaCy (for advanced NLP tasks)



Getting Started
Prerequisites

Python (v3.8 or higher)
pip (v20.0 or higher)

Installation

Clone the repository:
git clone https://github.com/ABHISHEKEKRE/ArticleAnalyzer.git
cd ArticleAnalyzer


Install dependencies:
pip install -r requirements.txt


Create necessary configuration files (e.g., for CSV input paths).

Run the pipeline:
python AbhishekeKRE_NLP.ipynb



Project Structure
ArticleAnalyzer/
├── text_articles/    # Directory for processed article text files
├── AbhishekeKRE_NLP.ipynb  # Main Jupyter notebook for the pipeline
├── INSTRUCTIONS.pdf  # Project instructions document
├── Output Data Structure.xlsx  # Output data structure details
├── README.md         # This file

Usage

Prepare a CSV file with article URLs and place it in the appropriate directory.
Run the AbhishekeKRE_NLP.ipynb notebook to scrape, process, and analyze articles.
Check the text_articles/ directory for processed article text files and refer to Output Data Structure.xlsx for feature details.

Current Progress

Successfully built a sentiment analysis pipeline for 100 articles.
Implemented web scraping with BeautifulSoup to collect article content.
Completed text preprocessing (tokenization, stopword removal, stemming/lemmatization).
Extracted and saved over 1,000+ feature records in CSV format.
Generated 100 text files for processed articles.

Contributing
Contributions are welcome! If you'd like to contribute to the Article Analyzer, please reach out to the repository owner.
Contact

GitHub: ABHISHEKEKRE
Project Link: https://github.com/ABHISHEKEKRE/ArticleAnalyzer


# Web Scraping and NLP Analysis Project
Web scraping is the process of extracting data from websites. In this project, we used the Python library Beautiful Soup in combination with the `requests.get` method to collect data from 114 different websites. Beautiful Soup is a popular Python library for web scraping, providing a convenient way to parse HTML and extract information from web pages.

This repository contains the code and data for a web scraping and natural language processing (NLP) project. The project involved scraping 114 articles from different websites, extracting their titles and content, and performing NLP analysis on the text data to gain insights into the articles.

## Web Scrapping
**Sending HTTP Requests**: We used the `requests.get` method to send HTTP GET requests to the URLs of the websites containing the articles we wanted to scrape. This method allowed us to retrieve the HTML content of the web pages.

With Beautiful Soup, we could navigate through the HTML structure of the web page to locate and extract the specific elements we needed. This often involved identifying HTML tags, classes, or other attributes associated with the data we wanted to scrape.


## Project Overview

In this project, we aimed to analyze a collection of articles to understand their textual characteristics and sentiment. The main features we analyzed include:

- Polarity Score: Measures the sentiment of the articles, indicating whether the text is positive, negative, or neutral.
- Subjectivity Score: Measures the subjectivity of the articles, indicating the degree to which the text is opinion-based.
- Average Sentence Length: Provides insights into the complexity and readability of the text.
- Percentage of Complex Words: Indicates the proportion of complex words in the text.
- FOG Index: A readability index that estimates the years of education required to understand the text.
- Word Count: The total number of words in each article.
- Syllables per Word (Average): Measures the average number of syllables per word in the text.
- Average Word Length: Measures the average length of words in the text.

## Project Structure

The project is organized into the following directories:

- `data/`: Contains the dataset of 114 articles in CSV format.
- `notebooks/`: Jupyter notebooks used for web scraping and NLP analysis.
- `scripts/`: Python scripts for web scraping and NLP analysis.
- `results/`: Output files and visualizations generated during the analysis.

## Getting Started

To reproduce the analysis or work with the code and data in this repository, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Explore the Jupyter notebooks in the `notebooks/` directory for step-by-step analysis.
4. Use the provided scripts in the `scripts/` directory for specific tasks such as web scraping and NLP analysis.

## Dependencies

The project uses the following libraries and tools:

- Python 3.x
- Jupyter Notebook
- Beautiful Soup for web scraping
- Natural Language Toolkit (NLTK) for NLP analysis
- Pandas for data manipulation


## Results and Insights

The project's analysis provides insights into the sentiment and textual characteristics of the articles. The results are available in the `results/` directory, including visualizations and summary statistics.

## License

This project is released under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, please feel free to reach out to [Your Name] at [your@email.com].

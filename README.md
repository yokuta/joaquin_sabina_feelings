
# Sentiment Analysis of Joaquín Sabina's Songs
This repository contains a quick and unoptimized script for analyzing the sentiment of Joaquín Sabina's song lyrics and their interpretations. The main goal is to compare the emotions expressed in the lyrics with how they are explained by users on the lyrics website. The analysis is performed using web scraping and sentiment analysis techniques.


## Table of Contents

- [Features](#Features)
- [Requirements](#Requirements)
- [Usage](#Usage)
- [Limitations](#Limitations)
- [Future Improvements](#Future-Improvements)

## Features
-  **Web Scraping:** Extracts song lyrics and their corresponding user explanations from letras.com.
-  **Sentiment Analysis:** Uses three sentiment analysis tools (TextBlob, VADER, and PySentimiento) to evaluate the emotional tone of both the lyrics and their interpretations.
-  **Data Aggregation:** Organizes sentiment scores at both the individual song level and the album level.
-  **Visualization:** Generates Sankey diagrams and a timeline to illustrate sentiment trends.

## Requirements
The script is written in Python and relies on the following libraries:
- requests
- BeautifulSoup
- pandas
- TextBlob
- VADER
- PySentimiento
- matplotlib
- seaborn

## Usage
Run the Jupyter Notebook (sabinaExtract.ipynb) to execute the scraping and sentiment analysis.




## Limitations
-  Not optimized: This script was written quickly and is not optimized for efficiency.
-  Potential website changes: If the structure of letras.com changes, the scraper may break.
-  Sentiment accuracy: Sentiment analysis tools have limitations, especially with poetic or figurative language like song lyrics.

# NLP Project: Sentiment Analysis in Twitter

## Project Overview

This project, developed by Ahmed Abdelmounaim Belkhoumali and Smail Doudou, is housed in a Jupyter notebook and focuses on sentiment analysis of Twitter data, particularly exploring sentiments related to the keyword 'vaccine'. Our specialization in Data Science and AI has guided our approach to effectively analyze tweet sentiments using Python.

## Getting Started

### Prerequisites

Ensure you have the following Python libraries installed to run the notebook:

```bash
!pip install emoji
!pip install vaderSentiment
```

### Installation

Clone the repository to your local machine to get started:

```bash
git clone https://github.com/bmounim/Natural-Language-processing-project.git
```

## Notebook Structure

The Jupyter notebook contains the following key sections:

1. **Authentication**: Setting up Twitter API keys for data extraction.
2. **Getting Tweets**: Using Tweepy to fetch tweets based on the keyword 'vaccine'.
3. **Cleaning Tweets**: Preprocessing tweets to remove unwanted characters and emojis.
4. **Sentiment Analysis**: Analyzing tweet sentiments using TextBlob and VaderSentiment.
5. **Data Visualization**: Visualizing the results through pie charts and word clouds.

## Usage

Open the Jupyter notebook and run the cells sequentially to:

- Authenticate with Twitter API.
- Extract and clean tweets related to a specific keyword.
- Perform sentiment analysis on the cleaned tweets.
- Visualize the sentiment distribution and common words.

## Results

The notebook will output:

- A cleaned DataFrame of tweets with sentiment analysis results.
- Visual representations of sentiment distributions and word frequency.

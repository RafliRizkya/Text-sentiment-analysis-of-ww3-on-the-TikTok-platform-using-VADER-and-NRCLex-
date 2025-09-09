# Text Sentiment Analysis of \#WW3 on TikTok using VADER and NRCLex

[](https://www.python.org/downloads/)
[](https://opensource.org/licenses/MIT)

## 1\. Overview

In an era of rapid information dissemination, social media platforms like TikTok have become critical arenas for public discourse on global events. This project delves into the public sentiment surrounding the trending hashtag **\#WW3** by applying Natural Language Processing (NLP) techniques.

The primary objective is to capture and analyze the polarity of opinions (positive, negative, neutral) and the underlying emotional landscape (fear, anger, joy, etc.) within TikTok comments. By doing so, this analysis provides a data-driven snapshot of public reaction and emotional dynamics in response to a significant global issue.

## 2\. Key Features

  - **Data Cleaning & Preprocessing:** Implements robust techniques to clean and standardize raw TikTok comment data, removing noise such as URLs, special characters, and stopwords to prepare it for analysis.
  - **Sentiment Polarity Analysis:** Utilizes `VADER` (Valence Aware Dictionary and sEntiment Reasoner), a lexicon-based tool optimized for social media text, to classify comments into **positive**, **negative**, or **neutral** categories.
  - **Emotion Detection:** Employs the `NRCLex` library to identify and quantify a spectrum of eight basic emotions (fear, anger, joy, sadness, surprise, etc.) and two sentiments within the text.
  - **Insightful Data Visualization:** Generates clear charts and graphs (e.g., pie charts, bar plots, time-series plots) using Matplotlib and Seaborn to visualize sentiment distributions and emotional trends.
  - **Word Frequency & Cloud:** Conducts word frequency analysis and creates word clouds to highlight the most prominent terms and topics of discussion within the comments.
  - **Temporal Analysis:** Includes capabilities to track how sentiment and emotions evolve over a specific period, revealing shifts in public opinion over time.

## 3\. Methodology Workflow

The project follows a systematic workflow:

1.  **Data Collection:** Gathering comment data from TikTok posts under the `#WW3` hashtag.
2.  **Data Preprocessing:** Cleaning the text by removing irrelevant characters, converting to lowercase, and tokenizing the sentences.
3.  **Sentiment Analysis:** Applying the VADER sentiment analyzer to each comment to obtain polarity scores (positive, negative, neutral, and compound).
4.  **Emotion Analysis:** Using NRCLex to process each comment and generate a frequency distribution of associated emotions.
5.  **Aggregation & Visualization:** Aggregating the analysis results and using Matplotlib/Seaborn to create visual representations of the findings for easy interpretation.

## 4\. Tools and Technologies

  - **Core Libraries:**
      - `VADER (vaderSentiment)`: For sentiment polarity analysis.
      - `NRCLex`: For emotion classification.
  - **Data Manipulation & Analysis:**
      - `Pandas`: For data structuring and manipulation.
      - `NumPy`: For numerical operations.
  - **Visualization:**
      - `Matplotlib`: For creating static and interactive plots.
      - `Seaborn`: For enhanced statistical data visualization.
      - `WordCloud`: For generating word clouds.
  - **Environment:**
      - `Jupyter Notebook`: For interactive development and analysis.

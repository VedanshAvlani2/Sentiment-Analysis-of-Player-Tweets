# Sentiment Analysis of Player Tweets

## Overview
This project analyzes Twitter sentiment towards three different players using **Tweepy** and **TextBlob**. It fetches tweets related to the players, processes them, and determines their sentiment polarity. The results are visualized through bar charts, helping to compare fan sentiment for each player.

## Features
- **Twitter Data Extraction**: Fetches tweets using Tweepy API.
- **Text Cleaning**: Removes URLs, hashtags, mentions, and newline characters.
- **Sentiment Analysis**: Classifies tweets as positive or negative based on polarity scores.
- **Player Comparison**: Determines which player has the highest positive sentiment.
- **Data Visualization**: Displays sentiment distribution and player comparison using Matplotlib.

## Technologies Used
- **Python** (Primary programming language)
- **Tweepy** (Twitter API integration)
- **TextBlob** (Sentiment analysis)
- **Pandas** (Data manipulation)
- **Matplotlib** (Data visualization)
- **Selenium** (Automated search via Google)

## Setup Instructions
1. **Install Dependencies**:
   ```bash
   pip install tweepy textblob pandas matplotlib selenium
   ```

2. **Set Up Twitter API Credentials**:
   Replace the API keys in `main.py` with your own credentials.

3. **Run the Script**:
   ```bash
   python main.py
   ```

4. **Follow On-Screen Prompts**:
   - Enter the match to search on Google.
   - Enter three player names for sentiment analysis.

## Insights Gained
- Determines which player has the most positive fan sentiment.
- Identifies trends in public opinion using Twitter data.
- Provides graphical comparisons of sentiment scores.

## Future Enhancements
- Automate real-time tweet fetching.
- Implement a graphical user interface (GUI).
- Expand to analyze sentiment across multiple social media platforms.


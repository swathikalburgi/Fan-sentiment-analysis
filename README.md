# Fan sentiment analysis
Can the voice of fans help us understand Formula 1 better? <br/>
This project says **yes** (and uses natural language processing to decode what fans feel about drivers, races, and events).<br/>

# About this project
By analyzing tweets and social media posts around Formula 1, this project captures the emotional pulse of fans during race weekends. Using sentiment analysis and machine learning, it predicts whether fan sentiment is positive, negative, or neutral, helping teams and analysts gauge the off-track mood.<br/>

# Features
💬 NLP-based sentiment classification on F1-related tweets
🧹 Text preprocessing and feature engineering 
📈 Sentiment trends by driver, team, and race events
🎯 Model trained and evaluated with precision, recall, and F1-score 
🗂️ Predictions stored for race-week analysis and strategy feedback 

# Tech stack
- Python, pandas, NumPy
- scikit-learn
- NLTK/spaCY (for text processing)
- Streamlit
- Joblib

# How it works 
1. Scrape or collect tweets using F1-specific hashtags  
2. Clean and preprocess text (remove noise, tokenize, lemmatize)  
3. Convert text to numerical features using TF-IDF  
4. Train and evaluate a classification model  
5. Save the final model as `fan_sentiment_model.pkl`  
6. Predict future sentiment and visualize results

# More
This is Part 3 of a 3-part AI/ML series: 
- [Race outcome analysis](https://github.com/swathikalburgi/F1-race-outcome-analysis)
- [Weather impact analysis]  
- Fan sentiment analysis *(you’re here)*

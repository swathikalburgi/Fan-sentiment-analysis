# Fan sentiment analysis
Can the voice of fans help us understand Formula 1 better? <br/>
This project says **yes** (and uses natural language processing to decode what fans feel about drivers, races, and events).<br/>

# About this project
By analyzing fan posts and social media sentiment, this project uncovers how drivers and teams were perceived in the lead-up to Monza 2025.  
It uses NLP techniques to classify sentiment, highlight trending topics, and identify peak discussion hours. The goal: translate fan buzz into actionable insight.<br/>

# Features
💬 Sentiment classification of driver/team mentions (positive/negative)<br/>
📈 Trending terms and hashtags based on fan discussions <br/>
🕓 Activity heatmap showing when fans were most active <br/> 
🎯 Recommendations for teams based on sentiment trends <br/>

# Tech stack
- Python, pandas, NumPy
- scikit-learn
- TF-IDF Vectorization  
- VADER Sentiment Analysis  

# How it works 
1. Collect fan text data and preprocess it (cleaning, tokenization, etc.)
2. Apply sentiment analysis using VADER and rule-based logic
3. Extract key terms, peak hours, and sentiment scores
4. Save results to `fan_sentiment_analysis_results.csv`
5. Visualize insights and suggest recommendations for teams/drivers

# More
This is Part 3 of a 3-part AI/ML series: 
- [Race outcome analysis](https://github.com/swathikalburgi/F1-race-outcome-analysis)
- [Weather impact analysis](https://github.com/swathikalburgi/F1-weather-impact-analysis)
- Fan sentiment analysis *(you’re here)*
- [Project suite](https://github.com/swathikalburgi/F1-AI-ML-project-suite)<br/>

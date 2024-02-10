# Streaming-sentiments-and-text-mining
## Overview
The task, titled “Analyzing Netflix’s Trends: Streaming sentiments and text mining,” focuses on analyzing text data from the Netflix Movie and TV Show dataset to understand the sentiments and narratives in the streaming content industry. Utilizing Python libraries and NLTK for sentiment intensity analysis, the project aims to quantify emotional content and uncover trends in various dimensions such as genre, providing a data-driven narrative of the industry's landscape.

## Data Cleaning and Transformation
The preprocessing steps involved converting text to lower case, removing special characters and numbers, and converting 'date_added' to datetime format. Tokenization, stop words removal, and lemmatization were performed to refine the text data. Missing values in 'director', 'cast', and 'country' were handled by replacing them with a placeholder. The 'description' column was transformed using TF-IDF vectorization, preparing the text for machine learning models.

## EDA
The analysis involved sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner), frequency analysis, topic modeling, word clouds, and N-gram analysis. Sentiment scores were computed and analyzed through histograms, revealing a distribution with a peak around the neutral zone. Genre sentiment analysis was conducted by splitting and expanding genres, and average sentiment scores for top actors were plotted. A stacked column chart visualized sentiments of Netflix content by release year, showing a significant growth in content production and diverse emotional tones.

## Results of Analysis
### Sentiment Analysis: 
Revealed a significant neutral sentiment peak, with diverse emotional tones increasing as content production grew. Actors like Rupa Bhimani and Vatsal Dubey were associated with content having higher positive scores. Genres like 'Stand-Up Comedy & Talk Shows' had higher sentiment scores, while 'Crime TV Shows' and 'Horror Movies' scored lower.
### Text Mining Analysis: 
Common themes included words like "life," "family," and "love". Topic modeling showed patterns related to youth and family, indicating demographic preferences. Sentiment fluctuations over time varied depending on content themes and external societal influences. NER highlighted entities like "Johnson" and "New Orleans," pointing to specific geographical and character focuses. N-gram analysis spotlighted common settings and relationships.

## Conclusion and Recommendation
The analysis suggests a content strategy focused on life, family, and friendship themes, with an emphasis on genres with positive sentiment for marketing and content development. Personalization and recommendation strategies should integrate actor sentiment data and align with sentiment progression trends. Ethical considerations are crucial, ensuring sentiment analysis tools are applied responsibly and respectfully towards user privacy.

#  Music Recommendation System
A personalized music recommendation engine that uses sentiment analysis and user ratings to suggest songs tailored to each listener’s preferences.

## Project Overview
This project builds a content-based music recommender as we're focusing on suggesting songs similar to ones the users usually like and that mirrors human decision-making in music discovery. 
- Natural Language Processing (NLP) for analyzing user reviews
- Feature engineering using musical audio attributes (tempo, energy, valence)
- Cosine similarity for artist/song comparison
- User ratings to fine-tune recommendations
  
## Tools & Libraries Used
- Programming Language : Python 
- Libraries : pandas (data manipulation), NumPy (data manipulation, scikit-learn, TextBlob, seaborn (data visualization), matplotlib (data visualization)
  
## Dataset Overview
- User Reviews: Free-text feedback with associated star ratings
- Audio Features: tempo, valence, energy, acousticness, danceability.
- Artist Metadata: name, genre, popularity

## How It Works

### 1. Preprocessing & Cleaning
- Missing values handled 
- Normalization of numerical data
- Encoding of categorical features

### 2. Sentiment Analysis
- Extract polarity scores using TextBlob
- Aggregate sentiments per song / artist

### 3. Feature Engineering
- Construct feature vectors using sentiment, ratings, and audio data
- Normalize vectors for similarity calculation

### 4. Similarity Computation
- Apply cosine similarity between songs/artists
- Rank based on similarity and user preference

### 5. Recommendation Output
- Return top-N most similar and positively reviewed songs

## Results
Generated relevant song recommendations reflecting both musical style and tone.

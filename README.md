# Aurality-A-Music-Recommendation-System
Aurality is a web-based, mood-aware music  recommendation system that suggests songs based on their similarity in mood, style, and  genre.  The system employs a content-based filtering approach using audio features such as 
energy, danceability, acousticness, and tempo. It is developed with Python and Flask on the 
backend, using a preprocessed music dataset, and features a clean, responsive HTML/CSS 
frontend for user interaction. Recommendations are generated dynamically by identifying 
tracks most similar to the user’s input song using audio feature vectors. The model delivers 
highly relevant results and ensures a seamless user experience. 

##  Aurality UI 
-  Personalized Recommendations
   - Aurality suggests songs based on mood, energy, tempo, and acoustic features using a content-based filtering algorithm.

-  Powered by Machine Learning
  - Uses K-Nearest Neighbors (KNN) and audio feature vectors to recommend 
 songs that closely resemble a user’s input track.

-  Feature-Rich Audio Dataset
  - Built using a curated dataset of over 11,000 songs with features like danceability, acousticness, energy, valence, and more — sourced from Spotify and Kaggle.

-  Exploratory Data Analysis (EDA)
  - Includes in-depth feature analysis using heatmaps, PCA, and t-SNE visualizations to understand correlations and trends in music.

-  Real-Time API with Flask
   - Backend powered by Flask delivers instant recommendations in JSON format, ready for frontend integration.

-  Clean and Responsive Frontend
   - Simple yet user-friendly UI using HTML/CSS allows users to input songs and receive similar suggestions in real time.
 
 -  Visual Insights
    - Interactive plots and charts reveal how sound features influence recommendations, making the system explainable and transparent.

-  Lightweight and Efficient
    - No heavy model training — just smart use of preprocessed data and similarity-based recommendations using sklearn.

- 📡 Designed for Extendability
   - Modular code allows for future enhancements like Spotify API integration, real-time mood detection, and hybrid filtering.

- 🔁 Feedback-Ready
     - Built to support future implementation of user feedback loops for learning preferences and improving suggestions.

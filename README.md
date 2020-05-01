# Text-Analytics-on-Song-Lyrics
Project to perform sentiment/emotion analysis, topic modelling and document retrieval on a dataset of song lyrics.


Main dataset: File can be downloaded from kaggle : https://www.kaggle.com/artimous/every-song-you-have-heard-almost#Lyrics2.csv, File to download : Lyrics1.csv

1) Three different folders:

 a) Sentiment_Analysis
 b) Topic_modeling 
 c) Document_retrieval

2) In Sentiment_Analysis:

    Data_cleaning_final.ipynb -> Jupyter notebook for cleaning data and file generation for sentiment and emotion models

    Models_sentiment_emotion_analysis.ipynb -> Jupyter notebook for sentiment and emotion model

    Emotion_group_clustering_bands.jmp -> JMP where Clustering model built to detect common emotion bands

3) In Topic Modeling:

    LDA Model Building .ipynb -> Code to generate LDA model on whole dataset

    Visualize the topics-keywords by wordcloud.ipynb -> Word cloud visualization for topic and words

4) Document_Retrieval : Code to retrieve documents by key words and model built using LDA distribution results.

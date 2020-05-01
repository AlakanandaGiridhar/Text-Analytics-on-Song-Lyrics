# Text-Analytics-on-Song-Lyrics
Project to perform sentiment/emotion analysis, topic modelling and document retrieval on a dataset of song lyrics.


Main dataset: File can be downloaded from kaggle : https://www.kaggle.com/artimous/every-song-you-have-heard-almost#Lyrics2.csv, File to download : Lyrics1.csv

1) Four different folders:

 a) Datasets
 b) Sentiment_Analysis
 c) Topic_modeling 
 d) Document_retrieval

2) All the datasets,intermediate and final results are available in Datasets folder

3) In datasets:

    Emotional_scores_500.csv  -> File generated after cleaning and contains emotion scores retrieved using api of 500 bands

    negative-words.txt -> Lexicon negative words corpus used for sentiment analysis

    positive-words.txt -> Lexicon positive words corpus used for sentiment analysis

    Songs_clean_en.csv -> File represents cleaned songs after removing non-english songs of Lyrics1.csv

    Tagged_songs_combined.csv -> Csv file for human tagging for sentiment analysis

    Tagged_songs_combined_final.csv -> Csv file received after tagging and some cleaning

    top_words.csv -> Results from Topic modeling which are top words for each document

    Topic(0...7)_after.png -> Wordclouds of topics (Visualization)

    doc_topic_mixture -> Resultant file from Topic modeling (Doc - Topic distribution)


4) In Sentiment_Analysis:

    Data_cleaning_final.ipynb -> Jupyter notebook for cleaning data and file generation for sentiment and emotion models

    Models_sentiment_emotion_analysis.ipynb -> Jupyter notebook for sentiment and emotion model

    Emotion_group_clustering_bands.jmp -> JMP where Clustering model built to detect common emotion bands

5) In Topic Modeling:

    LDA Model Building .ipynb -> Code to generate LDA model on whole dataset

    Visualize the topics-keywords by wordcloud.ipynb -> Word cloud visualization for topic and words

6) Document_Retrieval : Code to retrieve documents by key words and model built using LDA distribution results.

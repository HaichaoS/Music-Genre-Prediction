COMP90049 Introduction to Machine Learning, 2020 Semester 2
Project 2: Music Genre Prediction from Audio, Metadata and Text Features

Student Name(s): Haichao Song
Python version: 3.7.2
Submission deadline: 5 PM 16 Oct 2020¶

Library
Sklearn: applying different kinds of supervised learning models.
Seaborn and peplos: plot different kinds of diagrams in exploration and model analysis.
NLTK and TF-IDF: handle most important words and stop words in text features.

Evaluate functions
All train, predict and evaluate functions are in this section and models call them to train and get prediction of datasets.

Preprocess and Exploration
Divided all features to 3 kinds:
1. Text: titles and tags
2. Metadata: loudness, tempo, time_signature, key, mode, type, duration.
3. Audio: vect_1 ... vect_148
it handles all features and make them suitable for applying different models.
Preprocess observation are applied in this section, including correlation, distribution, scatter plot, box plot and so on.

Models
Apply different kinds of models to our dataset and get their prediction accuracies.

Boost and Bagging:
Use adaptive boost and bagging to improve model performance.

Test
Get test csv to submit in Kaggle.
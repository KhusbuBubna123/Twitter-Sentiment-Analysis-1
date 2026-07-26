In this project, twitter data was used from Kaggle. 
Two datasets were used in this project.
In the first dataset,there were two classes Positve(4) and Negative(0).

Tweets were classified as either having Positive(4) 
or Negative(0) Sentiment. Naive Bayes Classifier versions like Bernoulli_Naive_Bayes Classifier was used 
since there are only two classes- Positive(4) and Negative(0).

In the second dataset,there were three classes Positive(1),Negative(-1) and Neutral(0).

Tweets were classified as either having Positive(1),Negative(-1) or Neutral(0) Sentiments. Naive Bayes Classifier versions 
like Multinomial_Naive_Bayes was used 
since there are multiple classes- Positive(1), Negative(-1) and Neutral(0).

Results:

The accuracy,f1_score and recall obatined were as follows:
Bernoulli Naive Bayes Using Count Vectorizer(Accuracy:74.89%)(f1_score:0.7451837102235976),(recall:0.7570463140127429)
Bernoulli Naive Bayes Using TF-IDF Vectorizer:(Accuracy:71.02%)(f1_score:0.7287687)(recall:0.7664466).
Multinomial_Naive_Bayes Using Count Vectorizer(Accuracy:70.07%)(Per-Class F1 Scores: [0.64649583 0.65921909 0.74411173]),(Per-Class Recall Scores: [0.58336816 0.55084285 0.87422652]
Multinomial_Naive_Bayes Using TF-IDF Vectorizer:(Accuracy:69.97%)(Per-Class F1 Scores: [0.46679081 0.71957469 0.75261927])(recall_score :[0.3142499 , 0.68080479, 0.90648682])

).

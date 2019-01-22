Welcome to my repository for the Toxic Comment Classification project!! This is a Natural Language Processing (NLP) project with 3 parts. 

This repository has the following files:

1. Jupyter Notebooks: These contain python codes and detailed descriptions for each part of project.
     1. [Part1: Tfidf + Logistic Regression](https://github.com/math470/Toxic-Comment-Classification/blob/master/Toxic%20Comment%20Classification%20Part1%20Tfidf%20%2B%20Logistic%20Regression.ipynb) 
        Toxic Comment Classification Part1 Tfidf + Logistic Regression.ipynb 
        
        - I showed Tfidf + Logistic regression can make good predictions for toxic comment classifications (AUC: .9745)
        - I found some bad words are hidden in disguised forms, which have zero coefficients in the logistic regression model. 
      
     1. [Part2: GloVe + LSTM in Keras](https://github.com/math470/Toxic-Comment-Classification/blob/master/Toxic%20Comment%20Classification%20Part2%20GloVe%20Embedding%20%2B%20LSTM.ipynb) Toxic Comment Classification Part2 GloVe Embedding + LSTM.ipynb
    
        - I tried Deep Learning models with GloVe word embeddings and LSTM on the Keras framework (AUC: 0.9564)
        - I improved the performance using some simple ensemble methods (AUC: 0.9770)
      
     1. [Part3: More Cleaning](https://github.com/math470/Toxic-Comment-Classification/blob/master/Toxic%20Comment%20Classification%20Part3%20More%20Cleaning.ipynb) Toxic Comment Classification Part3 More Cleaning.ipynb 
    
        - I transformed the hidden bad words found in Part1 into actual words.
        - After cleaning, the simple logistic regression model performed even better than the best ensemble model found in Part2 (AUC: 0.9778).

1. [Final report:]() The final summary report will be added later. 

Datasets are too big to be stored here, but here is a [link](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) to the original datasets. 

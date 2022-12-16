# NLPFinalProject: Sentiment and Genre Classification
NLP Final Project determining a relationship between genre and valence.

Authors: 
Vivienne Kupiecki
Minh Le
Dylan Leddy
Ryan Clark

Primary Libraries Used: 
- NLTK 
- Pandas
- Scikit (Classification Models) 
- OpenML (API for downloading dataset) 
- NumPy 
- Transformers (Autotokenizer, DistilBERT) 
- Datasets  
- Genism (Wordtovec) 

Please see HuggingFace's DistilBERT for more information about distilBERT:  
https://huggingface.co/docs/transformers/model_doc/distilbert 

Files:
- NLP Final Project: Classification - Shows how we formatted our data, set up word2vec embeddings, 
  then fit our data into different baselines and clasffifiers.
- NLP Final Project: LM - Shows how fit our data into language models like BERT in order to attempt 
  to improve accuracy. In this file we ran bert 4 times.  Once with pop as a genre, once without.
  Once with 5 valence bins, once with 2.
- NLP Final Project: Fine Tuning - Shows how we picked value for KNN model and regrularized for Logistic regression.
  
Contribution Statement: 

Vivienne: 
- Binned valence data into five categories and ran baseline metrics for both valence and genre 
- Created graphs for classification models (KNN, etc.) and genre/sentiment trends 
- Separated training and testing data for initial model testing
- Helped with the implementation of BERT, such as researching the right model and fine-tuning parameters 

Ryan: 
- Took our data and made them into word embeddings so that we could fit them into models.
- Found predicted vs expected results for 5 different models (GaussianNB, SGD, Logistic Regression, MLP, KNN)
- Using these models, found the trend between genre and valence.
- Helped with the implementation of BERT, such as formatting the data into dataframes/csv files so that BERT accepted our data.

Minh: 
- Found datasets from openML
- Researched how to fetch data using built in function in sklearn
- Did some fine tuning on logistic regression and KNN models
- Created graphs to visualize data in 3d space and view error rate as we changed regularization constant for logisitic regression and k for knn models

Dyan: 

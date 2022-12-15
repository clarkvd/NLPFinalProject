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
  
Contribution Statement: 

Vivienne: 
- Binned valence data into five categories and ran baseline metrics for both valence and genre 
- Created graphs for classification models (KNN, etc.) and genre/sentiment trends 
- Separated training and testing data for initial model testing
- Helped with the implementation of BERT, such as researching the right model and fine-tuning parameters 

Ryan: 

Minh: 

Dyan: 

# ner_person_name
Named entity recognition using different approaches
I used different approaches and classifiers on the problem of Named entity recognition.

1.In the notebook classifiers.ipynb 4 classifiers namely Perceptron,Stochastic Gradient Descent,MultinomialNB and passive aggresive classifiers were used and results were compared.
Results were as follows:
Perceptron-Precision:0.49,Recall:0.82,F-Measure:0.57        
SGD-Precision:0.75,,Recall:0.82,F-Measure:0.76        
Multinomial NB-Precision:0.82,Recall:0.82,F-measure:0.82        
PGC-Precision:0.38,Recall:0.65,F-measure:0.38       

2.Part of speech tagging:In the notebook nltk.pos_tag.ipynb,I used the nltk package of Python-the pos_tag method to extract the tags which are proper nouns.The results were fairly similiar to the labels.

3.In the notebook word2vec.ipynb,I have tried out the Word2Vec embeddings and the relationships between different words depending on the context.

# ner_person_name
Named entity recognition using different approaches
I used different approaches and classifiers on the problem of Named entity recognition.
1.In the notebook classifiers.ipynb 4 classifiers namely Perceptron,Stochastic Gradient Descent,MultinomialNB and passive aggresive classifiers were used and results were compared.
Results were as follows:
                  Precision Recall  F-measure   Support
Perceptron         0.49      0.82      0.57        65
SGD                0.75      0.82      0.76        65
Multinomial NB     0.82      0.82      0.82        65
PGC                0.38      0.65      0.38        65

2.In the notebook nltk.pos_tag.ipynb I used the nltk package of Python especially the pos_tag method to extract the tags which are proper nouns.

logit_ml.py performs multiclass logistic regression on the cosine similarities between topic and text word vectors 

run as following 

python3 logit_ml.py labeled_data_4_27.json path/to/word2vec/model 

example 

python3 logit_ml.py labeled_data_4_27.json vec_models/word_vec_model_a.txt

Several word2vec models are in the vec_models/ directory 
word_vec_model_a.txt provided the best results and the paper was written using this model 
NOTE: if using any of the *.bin word2vec models you must change line 58 in logit_ml.py such that the binary argument is True (binary=True)

word2vect directory contains files used for making word2vec models from tweets we collected. 

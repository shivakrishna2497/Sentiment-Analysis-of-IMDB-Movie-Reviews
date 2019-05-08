# Sentiment-Analysis-of-IMDB-Movie-Reviews


The IMDB movie reviews dataset is a set of 50,000 reviews, half of which are positive and the other half negative.     The dataset is available online and can be either directly downloaded from Stanford’s website or obtained by running in a terminal (Linux):


wget http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz    


Then, we need to extract the dowloaded files. You can once again either do it manually or by running:    


tar -zxvf aclImdb_v1.tar.gz


Steps Followed :

1) Getting the Dataset


2) Loading the Dataset


3) Text Preprocessing


4) Model Building 


5) Improving the Current Model


Here, following some very basic steps and using a simple linear model, I was able to reach as high as an 83.67% accuracy on the IMDB dataset.To realize how good this is, a recent state-of-the-art model can get around 95% accuracy. So this isn’t bad at all, but there is still some room for improvement.


then I trained a new Linear SVM on TF-IDF features simply by replacing the CountVectorizer with a TfIdfVectorizer. This results in an accuracy of 88.66%, which is a 2% improvement over using BOW features.



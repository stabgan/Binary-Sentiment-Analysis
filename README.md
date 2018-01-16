### Natural-Language-Processing


# In this project I applied my knowledge of Machine Learning to predict binary sentiment of customers of a Restaurant and trained it on 800 reviews and tested it on 200 reviews .
 
In this project I faced a challenge to selcect the correct Naive Bayes Model .I tried the classic ones like The 
# Gaussian Naive Bayes 

![Server fetching image down ](https://qph.ec.quoracdn.net/main-qimg-116dbe9be09978ff474ace041079d1a0)

and 

# Multinomial Naive Bayes

![Server fetching image down ](https://image.ibb.co/jXuUgm/Screen_Shot_2018_01_17_at_12_23_35_AM.png)

but , I finally found that using 600 max_features and Using Bernoulli's Naive Bayes gives me the best result :

" there may be multiple features but each one is assumed to be a binary-valued (Bernoulli, boolean) variable. Therefore, this class requires samples to be represented as binary-valued feature vectors; if handed any other kind of data, a BernoulliNB instance may binarize its input (depending on the binarize parameter). " - Scikit learn Docs

![Server fetching image down ](https://image.ibb.co/fMOSZ6/Screen_Shot_2018_01_17_at_12_26_36_AM.png)






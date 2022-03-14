# Password-Classifier
Project created for Cybersecurity lectures. The goal was examination of randomness of passwords with differents lenghts and strenghts (desribed as number 0,1,2 where 0 is the weakest and 2 is the strongest password). Data was from kaggle but unfurtunately it was deleted from the site. Techniques used in this project: 
1. Natural Language Processing - transofrming passwords using [TfidfVectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)
2. Supervised Machine Learning - classification of password strenghts using [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) with accuracy of a model = 0.985 nad precision for each class = 0.98

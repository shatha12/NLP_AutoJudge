# AutoJudge

## Abstract
Artificial intelligence is being utilized in many domains , and the legal system is no exception. Under Vision 2030, Saudi Arabia aims to implement sweeping reforms to the legal system to eliminate inconsistency, speed up verdicts and make the Kingdom’s judicial institutions more efficient.

Our project (AutoJudge) aims to match similar court cases and predict the judgment results according to the information based on fact determination, which consists of the fact description, the basic information of defendant, and the court view.

## Data
The dataset contains around  3304 rows and 15 columns.  Data source is the Supreme Court of the United States from 1955 to 2021 (Kaggle)


## Algorithms
Pre-processing
1. Drop nulls and duplicates
2. Remove any digits and special characters
3. Remove Stop Words (domain , English )
4. Convert to Lower Case
5. Remove HTML tags and URLs


## Models

1. Several Classificatio models were used such as : Logistic  Regression , KNN ,  SVM ,MLP classifier, Naive Bayes,Ensamble
2. we used topic modeling (LDA , LSA , NMF , Corex ) and the best one was corex
3. We picked the model with the highest testing accuracy score : Ensamble.

## Model Evaluation and Selection
1. The dataset observations were split into 80/20 .
2. The evaluation of our models was based on Testing accuracy score.

## Tools
Tools: 
- Python, and Jupyter Notebook 
- Libraries: Pandas, Numby, Sklearn, and Matplotlib ,Seaborn , Pickles , NLTK , Feature extraction (TFIDF) Decomposition (NMF, LDA, LSA , corex).




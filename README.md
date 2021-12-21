# AutoJudge
Artificial intelligence is being utilized in many domains as of late, and the legal system is no exception.
Under Vision 2030, Saudi Arabia aims to implement sweeping reforms to the legal system to eliminate inconsistency, speed up verdicts and make the Kingdom’s judicial institutions more efficient.
Our project (AutoJudge) aims to predict the judgment results according to the information based on fact determination, which consists of the fact description, the basic information of defendant, and the court view.
## Question/Need :
The main goal of this project is to build unsupervised learning models that predict the judgment results
We are going to bulid different models and compare them to use the best model.
## Data Description :
The dataset from this this project is from kaggle
In total, the data consists of 3304 rows and 15 columns.
| Columns        | Description  |
| ------------- |:-------------:|
| ID   | unique ID |
| name      |      |
| href|    |
|docket| |
|term||
|first_party||
|second_party| |
|facts| |
|facts_len| |
|majority_vote||
|minority_vote||
|first_party_winner|if true means that the first party won, and if false it means that the second party won|
|decision_type||
|disposition||
|issue_area| |                                                           |
## Tools :
The main technologies and libraries that will be used are:
- Technologies: Python ,Jupyter Notebook , Canva
- Libraries:Pandas,BeautifulSoup and ,Matplotlib ,Seaborn ,NumPy ,sklearn ,  NLTK , Feature extraction (TFIDF) Decomposition (NMF, LDA, LSA)
## MVP :
New


# AutoJudge

Artificial intelligence is being utilized in many domains as of late, and the legal system is no exception.
Under Vision 2030, Saudi Arabia aims to implement sweeping reforms to the legal system to eliminate inconsistency, speed up verdicts and make the Kingdom’s judicial institutions more efficient.
Our project (AutoJudge) aims to predict the judgment results according to the information based on fact determination, which consists of the fact description, the basic information of defendant, and the court view.
## Question/Need :

The main goal of this project is to build unsupervised learning models that predict the judgment results
We are going to bulid different models and compare them to use the best model.
## Data Description :

The dataset from this this project is from kaggle
In total, the data consists of 3304 rows and 15 columns.
| Columns        | Description  |
| ------------- |:-------------:|
| ID   | Unique ID for Case |
| name      | Contains the names of the plaintiff and the defendant |
| href|   Case details link |
|docket| Docket number is the court's case number |
|term|Year of filing the case|
|first_party|First party name|
|second_party| Second party name|
|facts| The text of the lawsuit|
|facts_len| The number of character  in the sentence|
|majority_vote| Majority vote is more than half of the votes cast|
|minority_vote|Minority vote is less than half of the votes cast|
|first_party_winner|if true means that the first party won, and if false it means that the second party won|
|decision_type|The decision of the court |
|disposition|The current status or final outcome|
|issue_area| Cases types|                                                           |
## Tools :
The main technologies and libraries that will be used are:
- Technologies: Python ,Jupyter Notebook , Canva
- Libraries:Pandas,BeautifulSoup and ,Matplotlib ,Seaborn ,NumPy ,sklearn ,  NLTK , Feature extraction (TFIDF) Decomposition (NMF, LDA, LSA)

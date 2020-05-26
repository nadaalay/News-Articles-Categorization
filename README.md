## News Articles Categorization

### Table of Contents

1. [Project Overview and Motivation](#motivation)
2. [File Descriptions](#files)
3. [Installation](#installation)
4. [Results](#results)
5. [Licensing](#licensing)


## Project Motivation<a name="motivation"></a>

According to Internet Live Stats, in every second, around 9,000 tweets are posted; 3 million emails are sent and more than 90,000 GB of Internet traffic. So, we have a big amount of data in the internet. With such data, it is necessary to classify the data in categories. News contents are one type of data that should be categorized into groups to be easily accessed. News categorization helps users to access news of their interest without wasting time.
In this project, I will apply machine learning algorithms on news collected from CNN News website to construct a model that classify the news into groups.


## File Descriptions <a name="files"></a>
- One notebook file `News_Articles_Categorization.ipynb` which contains the code. 
- One data file `BBC News Train.csv` - The file contains a dataset of 1490 BBC News articles that classified into five categories: Business, Tech, Politics, Sport, Entertainment.
	- Data Fields:
		- ArticleId - Article id unique # given to the record.
		- Article - text of the header and article.
		- Category - cateogry of the article (tech, business, sport, entertainment, politics)
- Articles folder which contains four articles in text files.

## Installation <a name="installation"></a>
All libraries are avilable in Anaconda distribution of Python except the following libraries, you should install it:
- Natural Language Toolkit - [nltk library](https://www.nltk.org/).
- [XGBoost Python Package](https://pypi.org/project/xgboost/).
 

 
## Results<a name="results"></a>
In this project, I used CNN news dataset to classify the news text. I used TF-IDF feature extraction algorithm and six different machine learning algorithms: Support Vector Machine , Ada Boost, Gradient Boosting, XG Boost, Decision Tree, Multinomial Naive Bayes. Multinomial Naive Bayes was the best model and then I use it to classify new articles in order to check the model accuracy. . 

## Licensing <a name="licensing"></a>
The dataset is avilable in [Kaggle](www.kaggle.com/c/learn-ai-bbc/data) website. 

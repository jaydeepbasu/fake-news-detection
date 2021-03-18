# Fake News Detection

Fake news is false or misleading information presented as news. It often has the aim of damaging the reputation of a person or entity, or making money through advertising revenue.

In today's world prevalence of fake news has increased with the rise of social media.

Fake news can reduce the impact of real news by competing with it, a Buzzfeed analysis found that the top fake news stories often receives more engagement than top stories from major media outlets. It also has the potential to undermine trust in serious media coverage.

Moreover nowadays with the onset of bots fake news are getting created and being spread more than ever, the problem is real and hard to solve because the bots are getting better in tricking us, so we need better systems that help us understand the patterns of fake news to improve our social media, communication and to prevent confusion in the world.

## Data

The data for the following problem is [available on Kaggle.](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) 
Since the data has been added to the `data/` directory, cloning this repository would suffice.

## Pre-requisites

The project was developed using python 3.8.3 with the following packages.
- Pandas
- Numpy
- matplotlib
- seaborn
- Scikit-learn
- nltk
- wordcloud


## Files
- /notebook/Fake_News_Detection_NLP_LR_NB_DT_RF.ipynb : Jupyter Notebook with all the workings including pre-processing, modelling (Using NLTK library and Decision Tree Classifier, also tried out Naive Bayes, Logistic Regression,Random Forest followed up with hyperparameter tuning of each to find out the best model) and inference.
- /data/ : source data


## Acknowledgements

[Kaggle](https://kaggle.com/), for providing the data for this problem statement.
# Sentiment Detection Project

A joint project with my fellow student, a part of the course in Textual Data Analysis, is devoted to building a sentiment detection system that is a common task in Natural Language Processing. The project is composed of three milestones.

## Milestone I

Including:
* training sentiment classifiers on two datasets coming from different domains
* reporting performance of classifiers in terms of accuracy/precision/recall/F-score on the respective test sets
* performing a small qualitative assessment of the mistakes made by the classifiers.

## Milestone II

Including:
* testing classifiers on datasets opposite to ones used for training
* reproting gained results and drawing conclusions about the transferability of trained sentiment classifiers across different domains

## Milestone III

Including:
* translating one of the datasets used for training the sentiment classifier in the Russian language
* training a new sentiment classifier on produced dataset
* evaluating gained results both qualitatively and quanititatively


# Data used
1. <a href="http://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences">Sentiment Labelled Sentences Data Set</a>

The datasets contains sentences extracted from reviews of products, movies, and restaurants and labelled with **positive** or **negative** sentiment. The sentences are derived from three different websites
+ imdb.com (movies reviews)
+ amazon.com (product reviews, mostly mobile phones, headsets, and some other phone accessories)
+ yelp.com (restaurants reviews)

For each website, there are 500 positive and 500 negative sentences that ensure the dataset to be balanced. Altogether the dataset consists of 3,000 instances. Thus it's a medium sized which allows to browse the whole dataset as needed.

2. <a href="http://ai.stanford.edu/~amaas/data/sentiment/">IMDB reviews (Large Movie Review Dataset)</a>

The dataset provides sufficient data for both **positive** and **negative** sentiments which are uniformly distributed (label-balanced). Length of individual reviews is longer (than a single sentence like in `Sentiment Labelled Sentences Data Set`). Already known in NLP & ML community. Suitable for `binary sentiment classification`.

Please head over to [data folder](/data) for datasets used in the project.

# Packages used
* python       3.7.3
* re           2.2.1
* numpy        1.16.3
* pandas       0.24.2
* matplotlib   3.0.3
* seaborn      0.9.0
* scikit-learn 0.20.3
* eli5         0.8.2

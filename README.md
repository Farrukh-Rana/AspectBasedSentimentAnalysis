# AspectBasedSentimentAnalysis
Cross-Corporal Multi-Task Learning for Aspect-Based Sentiment Analysis (Using BERT)

The code in this repository is written mainly for the Organic dataset, Created and Maintained by the [Social Computing Research](https://www.social.in.tum.de/en/group/) group at [Technical University of Munich](http://www.in.tum.de/en/cover-page/).
There are two parts of the dataset:
* Annotated: This dataset which is composed of around 4.5K Relevant Annotated sentences is used for Supervised Learning.
* Unannotated: This, comparatively larger dataset, is composed of around 100K unannotated English comments from the same Organic domain. This dataset is being used to preTrain BERT model on the Organic domain, according to the Original [BERT Paper](https://arxiv.org/abs/1810.04805).

The goal of the project is to train one common model with different heads/outputs for each domain regarding sentiment analysis. This project was started in last week of April and is expected to finish by end of July.

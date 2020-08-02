# Analytics Vidhya\'s Janatahack: Customer Segmentation

Final rank yet to be disclosed. I didn\'t particularly like this competition because of very obvious data leakage which killed exercise of building models, feature engineering etc. There should be competitions with realistic datasets. 

## Description Of Problem

Given historical customer data, predict the segment of customer in new market which is similar to their existing market. There are total of 4 segments, A, B, C and D.


## Evaluation
Accuracy


## Data
Data can be downloaded from the contest page [JanataHack: Customer Segmentation - Problem Statement](https://datahack.analyticsvidhya.com/contest/janatahack-customer-segmentation/#ProblemStatement)

## Models
During the competition I built following models.

1. LightGBM
2. KNN


## Approach for Best Performing Model

Infer labels directly from training data + predict for rest using model. Final model was a LightGBM model.



PS: I write about Data Science, Machine Learning and AI at [dilbertai.com](https://www.dilbertai.com), where I share ideas and concepts I have learned over the course of my work, summarize research papers I read and practical knowledge I have gained from use cases I have worked on.

# Sentiment Analysis of Restaurant Reviews from Bangladeshi Food Delivery Apps
This is a research we did in Natural Language Processing Course, applying 3 major Sentiment Analysis model available and compared them. We made our own [dataset](http://doi.org/10.17632/wc87kpk6ks) from two popular food delivery apps in Bangladesh. Our study aims to provide valuable insights into the food industry and the field of natural language processing by conducting a thorough analysis of reviews from Bangladeshi food delivery apps.

## Introduction
This study aims to conduct sentiment analysis on restaurant reviews from Bangladeshi food delivery apps using natural language processing techniques. With the increasing popularity of food delivery apps in Bangladesh, understanding the sentiment of customer reviews can provide valuable insights for restaurant owners and food delivery app companies.

## Data Collection
We have created a dataset named "[Bangladeshi Food Delivery App Restaurant Reviews](http://doi.org/10.17632/wc87kpk6ks)" by gathering customer reviews of restaurants available on Foodpanda and Hungrynaki, which are two popular food delivery apps in Bangladesh.

## Methodology
We used three different models for the sentiment analysis, namely:

1. Robustly Optimized BERT Pretraining Approach (RoBERTa)
2. AFINN
3. DistilBERT, a distilled version of Bidirectional Encoder Representations from Transformers (BERT)

## Comparison Analysis
| Metric    | AFINN | RoBERTa | DistilBERT  |
|-----------|-------|---------|-------------|
| Accuracy  | 73%   | 74%     | 77%         |
| F1 Score  | 0.81  | 0.69    | 0.73        |
| Precision | 0.77  | 0.76    | 0.79        |
| Recall    | 0.86  | 0.63    | 0.68        |


## Results
The accuracy of the models evaluated were 74%, 73%, and 77% on RoBERTa, Afinn, DistilBERT respectively. That is, DistilBERT surpassed two popular sentiment analysis tools, AFINN and RoBERTa, in accuracy.


## Conclusion
This research highlights the importance of sentiment analysis in the food delivery industry and demonstrates the effectiveness of different models in performing this task. It also provides insights for businesses looking to use sentiment analysis to improve their services and products.

## Publication
Published in [ESCI 2023](https://esciioit.org).

DOI: [10.1109/ESCI56872.2023.10100214](https://doi.org/10.1109/ESCI56872.2023.10100214)

## Authors

<a href="https://github.com/errhythm/BDFoodAppSentiment/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=errhythm/BDFoodAppSentiment" />
</a>

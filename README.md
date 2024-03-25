# Binary Classification Model using BERT

![image](https://github.com/CJTAYL/news_class/assets/64110892/32da6a41-ea3a-4ed9-bf73-8cb129e5c87a)

Identifying the topic of news articles is often helpful for companies preparing to launch advertising campaigns. The purpose of this project is to demonstrate how the language model BERT or Bidirectional Encoder Representations from Transformers can be used to create a binary classifier to identify the topic of news articles.

### Data

The model was trained on a set of articles published by the Huffington Post between 2005 - 2012. The data were comprised of XX,XXX articles and were labeled prior to building the model. 

## Performance

The dataset had an equal number of positive (i.e., target topic) and negative instances (i.e., non-target topic); therefore, accuracy, precision, recall, and F1 Score were used to evaluate the model. 

The scores for each metric are listed below:
- Accuracy: 0.95
- Precision 0.94
- Recall: 0.95
- F1 Score: 0.95

Overall, the model was able to classify the articles accurately and discriminate between true positives, false positives, and false negatives.

## Application to Business Settings

The current project could serve as a template for data scientists working with clients who need support with targeted advertising. For instance, if a company planned on advertising with one publication, they could use a modified version of the model to determine which general interest publication (e.g., Time, The Atlantic) writes most often about the target topic. 

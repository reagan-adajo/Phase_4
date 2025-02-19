Phase IV Project
Reagan Adajo

Summary:

Business and Data Understanding:
### Business Problem
The company wants to develop a model that will assist in judging people's emotions about brands and products using Tweets on Apple and Google products. 
### Business Aim
To build a model that judges customer's emotions on brands and products using their sentiments
### Business Objectives
1. To find out the overall sentiments on Apple and Google products
2. To identify the products with the most positive and negative sentiments
3. To establish how the negative sentiments would be improved 
Data Understanding
Data was viewed and cleaned


The data was prepared by importing various python libraries along with various visualization to further explore and understand the data.
![alt text](image.png)

Modeling: A classification model was used on the data set to predict the where emotions were directed by the Tweets
![alt text](image-1.png)
The unique words were identified in the Tweets
![alt text](image-2.png)
Evaluation: The data was evaluated using Confusion Matrix. 
![alt text](image-3.png)

## Recommendation and Insights
1. The color orientation in the Confusion Matrix visualizes poor performance of the classification model. 
This implies that the actual verses predicted emotions in the tweets will be subject to misclassification.
2. The True and Predicted labels demonstrate a misalignment;
This implies that there will be a confusion in the results-interpretation from the model. 
3. The imbalanced color mapping highlights areas with problems in the model;
This depiction is useful in determining areas that needs to be improved in the model

## Conclusion
1. A single Tweet from Apple or Google cannot be use in predicting the emotions towards the product or brand.
2. Classification model has low accuracy and increased errors in predicting the emotions from a tweet text.
3. Tweet_texts are useful in identifying a problem with a product or brand from either Google or Apple, this informs on areas for improvement. 

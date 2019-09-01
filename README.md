# Amazon-food-fine-reviews-Dataset
Amazon Fine Food Reviews Analysis
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews 

EDA: https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

Attribute Information:

Id
ProductId - unique identifier for the product
UserId - unqiue identifier for the user
ProfileName
HelpfulnessNumerator - number of users who found the review helpful
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
Score - rating between 1 and 5
Time - timestamp for the review
Summary - brief summary of the review
Text - text of the review
On this data set knn classification is applied on 4 sets:
SET 1:ProfileName1HOT+Time+Summary-bow
SET 2:ProfileName1HOT+Time+Summary-tfidf
SET 3:ProfileName1HOT+Time+Review-bow
SET 4:ProfileName1HOT+Time+Review-tfidf
Code Refrence is taken from @harrismohammed Repository

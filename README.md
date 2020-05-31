# E-Commerce Women's Clothing Reviews

## Context

Natural Language Processing project using scikit-learn for Women's Clothing Reviews on an E-commerce website (23,487 reviews) using
multiple algorithms (SVM, Naive Bayes, Random Forest, KNN, and Logistic Regression) to classify them into good and bad reviews. Achieved 
a high accuracy with SVM. Also extracted the most frequently used ‘good’ and ‘bad’ words, the general polarity of sentiments in the 
reviews, the features that have positive correlations, etc.    

## Features 
This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

1. Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
2. Age (of the reviewing customer)
3. Title (of the Review)
4. Review Text
5. Rating (of the clothing article out of 5)
6. Recommended IND (Recommendation Index is a binary variable- 1 is recommended and 0 is not recommended)
7. Positive Feedback Count (Number of positive feedbacks given by the customer)
8. Division Name
9. Department Name
10. Class Name

## Analysis       
- Describe the data     
- Descriptive statistics, data type, etc.    
- Analyze the text comment/ review and share the findings  
- Convert the ratings into 2 classes  
- Class: Bad when Rating <=3  
- Class: Good otherwise   
- Develop a model to predict the Rating class 

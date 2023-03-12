# The 2nd team project. Data-Analysis-Amazon Alexa Reviews

## Objective/Goal
The goal is to create a model that determines negative or positive feedback.

## Role
We worked independently for 1 month for our 2nd team project to extract, clean, analyze, visualize, create model with diffrent classifier and fit the models.

## Data
This dataset consists of a nearly 3000 Amazon customer reviews (input text), star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots, Alexa Firesticks etc. for learning how to train Machine for sentiment analysis.

##Tools Used
Stopwords, wordcloud, Pipeline, CountVectorizer, TfidfTransformer, GridSearchCV, lemmatizer(Grouping different forms of words)
    
 ## Models Used
 We made 16 model for training:
    1 KNeighbors Classifier cv lem      
    2 Support Vector Classifier cv tfidf lem     
    3 KNeighbors Classifier cv    
    4 KNeighbors Classifier cv tfidf lem   
    5 Support Vector Classifier cv tfidf   
    6 KNeighbors Classifier cv tfidf  
    7 Random Forest cv tfidf     
    8 Random Forest cv tfidf lem     
    9 Random Forest cv lem    
    10 Random Forest cv 
    11 Support Vector Classifier cv lem  
    12 Support Vector Classifier cv 
    13 Decision Tree Classifier cv tfidf lem  
    14 Decision Tree Classifier cv tfidf 
    15 Decision Tree Classifier cv  
    16 Decision Tree Classifier cv lem
    
## Code
Code for this project can be found here: https://github.com/KIMVERONIKA/Amazon_Alexa/blob/main/27_10_2022_Veronika_amazon_alexa_review_classification.ipynb

## Results
The best models 11 is Support Vector Classifier Convectorizer Lematization has accuracy from train set 99% and the accuracy from test set 93%.
Decision Tree Classifier Convectorizer Lematization has precision from train set 99% and from test set 94%.

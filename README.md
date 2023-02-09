# The second team project.
Data-Analysis-Amazon Alexa Reviews
Alexa is a virtual assistant that works in a similar way to popular apps like Siri or Google Now. In other words, Amazon Alexa is an assistant that responds to voice commands and performs user tasks.
3000 reviews. Date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots, Alexa Firesticks etc. The goal is to create a model that determines negative or positive feedback.

0. Step we load the libraries
1. Step we upload dataset
2. We make visualization of the dataset
3. Showing Word Cloud Alexa 
4. We cleaning data, drop variables
5. We do lemmatizer(Grouping different forms of words)
6. Train the model and Evaluating the model use Random Forest Classifier, Decision Tree Classifier, Support Vector Classifier, KNeighbors Classifier.
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

Conclusion: The best models 11 is Support Vector Classifier Convectorizer Lematization has accuracy from train set 99% and the accuracy from test set 93%.
Decision Tree Classifier Convectorizer Lematization has precision from train set 99% and from test set 94%.

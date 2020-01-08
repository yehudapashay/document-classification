# document-classification

In this assignment we got as input many documents and the **goal**  is to predict it subject.

I worked with "Reuters-21578" text categorization dataset.
 
### How to run?
1. Install nltk package. You can use this video tutorial for that [Link to tutorial](https://www.youtube.com/watch?v=68aHmFcO-W4)
2. Download the train and test set from this links:
          train set : [Link](https://drive.google.com/file/d/1CLso1jKSGQjGF1S-b_WZ7xRWJa8lkSCO/view?usp=sharing)  
          test set: [Link](https://drive.google.com/file/d/1xTkrxJdodZRCJDPdYZ5RAsImIkNJ1ycY/view?usp=sharing)  
3. Change the path variable in the beginning of the code to the path of the data sets in yours computer.  

#### __Work Proccess:__
__Text pre-processing and exploration:__  
1. Read the data from files  
2. Clean the data  
3. Data exploration  
  
#### __Text pre-processing and exploration:__  
4. Feature extraction  
5. Classify using machine learning methods  
6. Tune the models and try to improve results  
7. Choose the best model  
  
The python labraries I mainly used are: Scikit-Learn, nltk, Pandas.
  
Data cleaning:
   1. Change all text to lowercase
   2. Tokenize the sentences to words (using nltk.tokenize)
   3. Remove stop-words (using nltk.corpus - stop words)
   4. Stemming the words using Porter Stemmer (nltk.stem - PorterStemmer)
  
Data exploration:  
I printed the top 10 common words from each category and saw what are the most common words.  
The common words was added to the stop words list and I run one more time stop words removal.  
  
Text pre-processing and exploration:  
Feature extraction was done by TfidfVectorizer and CountVectorizer.   
  
For classification we used: Naive Bayes, Decision Tree and SVM.  
The algorithm which gave us the best accuracy was SVM.  
We tried to imrpove our accuracy level and used GridSearchCV and entered parameters to improve.  
    
**You can use the Jupyter Notebook which is very commented.  
Yehuda.**  

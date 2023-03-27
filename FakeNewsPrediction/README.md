FAKE NEWS PREDICTION::-

      
        This project aim is to predict whether the news is real or fake. 
        The datasets used in this project is taken from kaggle website(https://www.kaggle.com/c/fake-news/data?select=train.csv)
        At last we will check whether our model is predicting the right prediction of fake news or not
MODULES AND LIBRARIES::- 
        1)Numpy
        2)Pandas 
        3)sklearn(TfidfVectorizer,train_test_spilt,svm,Logisticregresson,accuracy_score)
        4.nltk(corpus,stem.porter)
       
LIBRARIES FUNCTION::-
         nltk:-Used for natural language processing tasks, such as tokenization, stemming, tagging, and parsing
         TfidfVectorizer:-TfidfVectorizer is a class in the scikit-learn library that is used for converting a collection of raw documents into a matrix of TF-IDF features.
         PorterStemmer:-It is a widely used algorithm for stemming English words, and it works by applying a set of rules to reduce each word to its base or root form.
         
LOAD THE DATA::- 
         Load the data using the pd.read_csv functtion to read the data
         
CHECK FOR NULL VALUE::-
         Check and count whthere there is null value or not using dataframename.isnull().sum() functions
    
CONCAT THE DATA::-
         Concat the author and title data together with as content name
       
REPLACE THE NULL VALUE::-
         Replace the null value with the empty string

STEMMING::-
         Stemming is the process of reducing a word to its Root word. The words are converted into small letter.
        
TfidVectorize::-
         Convert the letters into the numeric value in which the system can understand properly
       
TRAIN_TEST::-
          We will split our data into train , test substes
   
PREDICTION::-
          We will make our model to predict the train datasets and find the accuracy score that how correct our model predict the values
          
GIVE VALUES::-
          Now we will provide an input to our data manually that can our model differentiate between the fake news and the reak news
          If our prediction is 0 then the news is real otherwise its fake
       

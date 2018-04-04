# spam-filtering

### Approach 

The dataset was obtained from http://spamassassin.apache.org/old/publiccorpus/ . The dataset contains nearly 1400 spam and non-spam files. 
The files are preprocessed by removing html tags,extarcting content,replacing all urls with httpaddr,numbers with the keyword number,dollar sign with the 
keyword dollar and so on. The content was stemmed using the famous PorterStemmer available in nltk. 

Features were extracted from the files and predictions regarding spam were made based on that. 

### References

Machine learning course by Andrew Ng - https://www.coursera.org/learn/machine-learning

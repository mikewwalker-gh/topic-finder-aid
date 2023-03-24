# topic-finder-aid
extract top x N-grams from chat transcript corpus - this example uses chat text from freely available ATIS CORPUS (https://www.kaggle.com/siddhadev/atis-dataset-from-ms-cntk)
Provides a technique to use N-grams - trigrams or bigrams, to discover the top ranked e.g, top 40 trigrams. This can be used as insights into developing a list of topics that were discussed during the chats. 
Mainly leverage NLTK library, preprossess the above mentioned corpus to only use the chat text column or use the inlcluded "Airline_Chat_UTF8.csv" file. 
see inline comments for preprocessing and processing.

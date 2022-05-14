# Fake-News-Detection
//
after downloading extract data.rar
//








Objective: The objective of the project was to create models which will help to identify fake news from real news, with the help of supervised learning. 


Data: Data have been obtained  for learning from the following source: https://data-flair.training/blogs/machine-learning-project-ideas/



Feature engineering: Obtained data contains 4 columns, the ID, title and text of the news, as well as a label (FAKE and REAL). For our project purposes we need the text of the news only, so we have dropped all the other columns. 
        Machine learning algorithms cannot work with raw texts directly, that is why we had to convert the texts into numeric features. This is called feature extraction or feature encoding. A popular and simple method of feature extraction with text data is called the bag-of-words model of text. A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things: A vocabulary of known words. A measure of the presence of known words. More specifically, we chose TF-IDF(term frequency-inverse document frequency) converter, which gives valuable insights for the machine, to be able to make sense of the texts and learn from them. TF-IDF is a statistical measure that evaluates the relevance of a word to a document and to a collection of documents. Two metrics are used: the number of times a word appears in a document, and the inverse document frequency of the word across a set of documents. 

Constructed models:  5 algorithms of supervised learning have been used in order to create a model which will accurately distingiush fake news based on the text.
                     1. Passive Agressive Classifier 
                     2. XGBClassifier
                     3. Logistic Regression
                     4. Desicion Tree
                     5. Random forest

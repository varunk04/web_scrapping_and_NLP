# web_scrapping_and_NLP
### This project aims to web scrapes the text data from websites regarding the Artificial intelligence and implement's **Word2Vec** , a common method of generating word embeddings.

Word embeddings is a technique where individual words are transformed into a numerical representation of the word (a vector). Where each word is mapped to one vector, this vector is then learned in a way which resembles a neural network. 

The vectors try to capture various characteristics of that word with regard to the overall text. These characteristics can include the semantic relationship of the word, definitions, context, etc. With these numerical representations, you can do many things like identify similarity or dissimilarity between words.

Word2Vec Architecture:

The effectiveness of Word2Vec comes from its ability to group together vectors of similar words. Given a large enough dataset, Word2Vec can make strong estimates about a word’s meaning based on their occurrences in the text. 

These estimates yield word associations with other words in the corpus. For example, words like “King” and “Queen” would be very similar to one another. When conducting algebraic operations on word embeddings you can find a close approximation of word similarities. 

For example, the 2 dimensional embedding vector of "king" - the 2 dimensional embedding vector of "man" + the 2 dimensional embedding vector of "woman" yielded a vector which is very close to the embedding vector of "queen". Note, that the values below were chosen arbitrarily.

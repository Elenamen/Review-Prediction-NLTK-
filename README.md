# Review-Prediction-NLTK-

Tokenization--> breaking down the document into different words

Stemming --> NLP technique that reduces words to their root/base form (ie. retrieval,retrieved,retrieves >> retrieve)
              Part of the NLP pipeline process
              Different algorithms for stemming, ie.Porter stemmer,Snowball,Lancaster
              Input of the stemmer: tokenized words

Lemmatization --> Process of reducing a word to its base form, but unlike stemming, it takes into account the context of the word, and it produces a valid word, unlike stemming which may produce a non-word as the root form.

Bag of word model --> A bag-of-words is a representation of text that describes the occurrence of words within a document. 
It involves two things:
                A vocabulary of known words.
                A measure of the presence of known words.
The simplest scoring method is to mark the presence of words as a boolean value, 0 for absent, 1 for present.
Useful source: https://machinelearningmastery.com/gentle-introduction-bag-words-model/

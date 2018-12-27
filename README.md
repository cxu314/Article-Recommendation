# Article Recommendation

The goal of this project is to make a simple article recommendation engine using a semi-recent advance in Natural Language Processing (NLP) called Word2Vec. In particular, a "database" from Stanford's GloVe project trained on a dump of Wikipedia is used. The project involves reading in a database of word vectors and a corpus of text articles then organizing them into a handy table (list of lists) for processing.

I also build a web server that displays a list of BBC articles on AWS. Clicking on one of those articles takes you to an article page that shows the text of the article as well as a list of five recommended articles.
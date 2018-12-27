# Article-Recommendation

The goal of this project is to make a simple article recommendation engine using a semi-recent advance in natural language processing called word2vec (or just word vectors). In particular, a "database" from Stanford's GloVe project trained on a dump of Wikipedia is used. The project involves reading in a database of word vectors and a corpus of text articles then organizing them into a handy table (list of lists) for processing.

Around the recommendation engine, I built a web server that displays a list of BBC articles for URL `http://localhost (testing)` or whatever the IP address is of your Amazon server (deployment).
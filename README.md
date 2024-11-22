# Word2Vec-
Suppose we have a ‘center’ word c and a contextual window surrounding c. We
shall refer to words that lie in this contextual window as ‘outside words’. 

Figure 1: The word2vec skip-gram prediction model with window size 2

<img width="488" alt="Screenshot 2024-11-21 at 8 37 34 PM" src="https://github.com/user-attachments/assets/e0241b49-4dfd-49ee-a80e-2bead5ff1e95">

For example, in Figure 1 we see that the
center word c is ‘banking’. Since the context window size is 2, the outside words are ‘turning’, ‘into’, ‘crises’, and ‘as’.
The goal of the skip-gram word2vec algorithm is to accurately learn the probability distribution P(O|C). Given a
specific word o and a specific word c, we want to calculate P(O = o|C = c), which is the probability that word o is
an ‘outside’ word for c, i.e., the probability that o falls within the contextual window of c.


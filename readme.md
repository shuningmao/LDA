# There are 2 files, LDA and Word2Vec -- Similar_Words.

## LDA: Latent Dirichlet Allocation, is an unsupervised method to classify documents into selected number of topics.  LDA relies on the topic distribution per document, the word distribution per topic, topic for the word in the documents and the word. Application: a random 10k articles from Wikipedia can be grouped into 10 (or any other number) of topics using this algorithm. Advantage: unsupervised, need very few human-input to generate the result

## Word2Vec: turn words into vectors/ word embeddings, each word can be matched with high dimension vectors for potential meaning. Application: 1. similar_words, find similar words by the closeness of the embedding vectors. 2. pre-processing the textual data for machine learning algorithm (e.g. in Convolutional Neural Network)


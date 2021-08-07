# word2vec-model
Word2vec is a group of related models that are used to produce word embeddings. These models are shallow, two-layer neural networks that are trained to reconstruct linguistic contexts of words. In this project, I used word2vec models in Embedding layer of my architecture to predict whether a comment is in favor of some product or on the other hand, against some product.

The Dataset used is the comments in the Digikala online shopping website. These comments are scraped from ![](Digikala.com) and have been labeled based on the stars people who had bought the products gave to them. As the data provided is noisy to some extent, combination of different features and also different pre-processing techniques was carried out to get the best results from the dataset.
For more clarification regarding the labels in the dataset: 

1 indicates suggesting others to buy 2 means otherwise 3 illustrate a neutral opinion about the product 4 means the person has rate the product, but not suggest whether to buy or not Finally the two or three digits number indicates the satisfaction percentage of the consumer with the preceding comment.

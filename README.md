# Word2vec with pure TensorFlow 2
I implemented Word2Vec using *skip-grams* and *negative sampling* with pure Tensorflow 2. I tried not to use any high-level function (such as Keras) and code at a** low-level**, so it is easier to understand what is going on inside a W2V model.

> If you just want to train a W2V and don't want to learn it, I highly recommend you to use the `gensim` package. This code is only a tutorial.

I commented on most of the code so it would be easier for you to understand it. The model is fairly simple.
# word-embedding-nn: Neural Network for Sentence Generation

### Step 1
I worked on this project in my NLP class (CS 4120). In this project, we cleaned and preprocessed two textual datasets - spooky authors and song lyrics - 
to train Word2Vec embeddings. We then visualized these embeddings in 2D space, to see their similarites and differences. You can see look at our .pdf file for 
more in-depth findings.

### Step 2
Next, we used these datasets to create feedforward neural networks. We used ngram based sequences to create our training set 
(with n-gram of length n, we are given n-1 tokens, and have to predict the nth token). We generate example sentences and compare them between both datasets.
You can see our findings for yourself in our .pdf file.

Ultimately, this project was my first time implementing a neural network, and showed me its usefulness in probability distributions (i.e. the softmax activation function). If I were to pursue next steps, I would build a more complex neural network and see if I can get more "correct" results: as in sentences that make more sense.

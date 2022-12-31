### Simple word2vec

This document was to train and test word2vec model
The code has three parts.
The first part is to train the model and is almost exactly this: https://www.tensorflow.org/tutorials/text/word2vec , but changed slightly, for the sake of learning.
The second and third part are from this: https://radimrehurek.com/gensim/auto_examples/tutorials/run_word2vec.html, but changed to a considerable degree.

The differences are:
1) Changed the input dataset.
2) Changed the negative sample number, window size, batchsize, ...
3) changed the design of the model.
4) wrote a similarity function at the end, the results were bad.
5) imported genism and tested the results with genism, results were great.
6) Since results were good, trained GENISM with data, and the result was bad again :). (DATA ISSUE)


## Result:
I am pretty sure the model sucks unless we feed a very rich data.


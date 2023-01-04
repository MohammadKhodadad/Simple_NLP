### word2vec

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


#### Result:
I am pretty sure the model sucks unless we feed a very rich data.

### Name Entity Recognition

The code has two parts.
The script is from this: https://keras.io/examples/nlp/ner_transformers/ , but greatly changed.

The differences are:
1) Changed the input dataset format.
2) changed the design of the model.


#### Result:
I replaced the model with two very simple models, one word wise dense, and one with two layers of attention. Both were almost as good as the complicated transformer based model that the link suggests. I am not yet very expert at this, but seemed the data was too easy.


### TextGeneration
The code is based on shakespear dataset like word2vec.
Model was tested with multiple multihead attentions and lstms as well.

#### Result:
The data is very limited, so we cannot expect a good result. Besides, I didn't tune the model. Just tested a few architectures.
Generated sentences:
king of  the poor business to the poor three and out of the gods i have been a man to the business.
king of  my brother then or i thank thee good sir in and i am too young i fear fearful grace.

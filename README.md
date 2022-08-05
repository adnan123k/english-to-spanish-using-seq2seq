# english-to-spanish-using-seq2seq
english-to-spanish-using-seq2seq is an application that translate english to spanish using DeepLearning, it uses encoder and decoder.<br />
the encoder uses Bidirectional LSTM so it could scan the sentence going forward and backward.<br />
the decoder uses LSTM that takes the previous hidden, cell state, word embedding vector and the context which been given by using attention.
# how to run it
there is two ways to use it:<br />
1-colab<br />
2-localy<br />
if you're using colab just upload the ipynb file and run it<br />
localy:<br />
1-you have to install python 3<br />
2-the recommended libraries<br />
3-install ide and open the .py file or .ipynb<br />
4-run it<br />
# the recommended libraries:
1-tensorflow<br />
2-keras<br />
3-numpy<br />
4-pandas<br />
5-matplotlib<br />
6-random
# reference:
https://360digitmg.com/rnn-and-its-variants-in-artificial-intelligence
https://towardsdatascience.com/word2vec-explained-49c52b4ccb71
https://towardsdatascience.com/intuitive-understanding-of-attention-mechanism-in-deep-learning-6c9482aecf4f
https://machinelearningmastery.com/teacher-forcing-for-recurrent-neural-networks/

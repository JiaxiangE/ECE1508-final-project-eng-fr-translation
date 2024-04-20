Group 33: Jiaxiang E, Yixu Ye, Shuqi Yang

Stage 1：Data Preprocessing
Running this part of the code will result in cleaned bilingual data.

Stage 2：Word2Vec
Running this part of the code will get the coordinates of the word mapped to the vector.

Stage 3：Recurrent Neural Network(RNN)
There are six mods on RNN in this section, which are VecMap RNN, Basic RNN, GRU RNN, LSTM RNN, Seq2GRU RNN, Seq2LSTM RNN. Open source resources on github are used when running vecmap. (Link: https://github.com/artetxem/vecmap)

Stage 4: Seq2Seq Transformer
Optimized RNN models for machine translation tasks based on the Transformer architecture.

Additional files that need to be imported into colab:
TRAIN.DICT: This file is used to generate -semisupervised bilingual mapping files. This file is not needed if unsupervised is used.
TEST.DICT: This file is used to evaluate your mapped embeddings in bilingual lexicon extraction.
Test_Space_for_LSTM_RNN.ipynb: This file is used for LSTM fine-tuning experiments and testing purposes.



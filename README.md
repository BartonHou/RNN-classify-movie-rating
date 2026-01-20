A simple RNN use to classify movie rating\
Dataset used- https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews \
Word2Index -> Pad -> Embedding layer -> RNN\
Use pad_sequence for batch training, use pack_padded_sequence to get rid of noise created by padding

This folder contains the 3 models based on matrix factorization:
1. matrix\_factorization.ipynb -- used for matrix factorization done using convolutional autoencoder image representations and pre-trained CNN image representations
2. mmeda1\_arch.ipynb -- MMEDA - I architecture using convolutional encoder-decoder and vanilla encoders, with matrix factorization reconstruction
3. mmeda2\_arch.ipynb -- MMEDA - II architecture using convolutional encoder-decoder and vanilla autoencoders, with matrix factorization reconstruction

matrix\_creation.ipynb is used to create matrices, used by matrix factorization methods.

Other experiments:
1. Some additional experiments carried out include concatenating the pre-trained CNN representations from GoogleNet, InceptionNet, VGG and ResNet and using this as one input matrix along with Word2Vec representations as the other input matrix for matrix factorization. This experiment is available in the file matrix\_factorization\_all\_cnn.ipynb.
2. We also tried to replace Word2Vec representations with SentenceBert representations. The associated files are also present in this folder.
3. We attempted to increase the Word2Vec representation dimensions to 300 as well.

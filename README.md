# pWord2Vec
This is a C++ implementation of word2vec that is optimized on Intel CPUs, particularly, Intel Xeon and Xeon Phi (Knights Landing) processors. It supports the "HogBatch" parallel SGD as described in "[Parallelizing Word2vec in Shared and Distributed Memory](https://arxiv.org/abs/1604.04661)". A short NIPS workshop version can be found [here](https://arxiv.org/abs/1611.06172). It also uses data parallelism to distribute the computation via MPI over a CPU cluster. 

The code is developed based on the [original word2vec](https://code.google.com/archive/p/word2vec/) implementation from Google.

##License
All source code files in the package are under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Code 
https://github.com/IntelLabs/pWord2Vec

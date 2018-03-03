# Multi-word Embeddings CNN for Identifying Informative Messages
- Simplified implementation of "Convolutional Neural Networks for Sentence Classification" paper

- We introduce a novel approach usingConvolutional NeuralNetwork   augmented   with   multi-word   embeddings.   The   concatenation of embeddings at the embedding layer is utilized to learn local feature for sentenceclassification.  Our  approach  combines  i)  diverse  version  of  pre-trained  wordembeddings   and   ii)   extracts   features   of   the   sentence   with   variable-size convolution  filter.  We  also  show  the  advantages  and  good  performance  whencompared with baseline methods in case of disaster data.
----
## Requirement
- tensorflow
- keras
- ...

----
## Running
- Configure home folder
- run with 'python train.py'
- Check output

----
## References

* [Kim, Yoon. "Convolutional neural networks for sentence classification." arXiv preprint arXiv:1408.5882 (2014)](https://arxiv.org/abs/1408.5882)

### CRF versus Vowpal Wabbit

This notebook shows a reimplementation of NER using Vowpal Wabbit in place of the CRF Suite example given in the tutorial here https://sklearn-crfsuite.readthedocs.io/en/latest/tutorial.html

TLDR - Vowpal Wabbit achieves the same algorithm performance, but at a much faster speed.  

The CRF implementation took 44s to train and the Vowpal Wabbit took 6s to train. They achieved similar f-score performance on the validation set.



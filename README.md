# ICLR-reproducibility-challenge
Code modifications for ICLR Reproducibility Challenge

# Update the code
`mv rnn_cell_impl.py /usr/local/lib/python3.6/site-packages/tensorflow/python/ops/`

`mv n_step_lstm.py /usr/local/lib/python3.6/site-packages/chainer/functions/connection`

`mv lstm.py /usr/local/lib/python3.6/site-packages/chainer/functions/activation`

# Running the experiments
There are three different experiments:
Some of the experiments require different Tensorflow versions so it is suggested that each experiment be run in a separate virutal environment in order to avoid having version issues.

* Language Modeling:  
The original implementation can be found at: https://github.com/tensorflow/models/tree/master/tutorials/rnn/ptb

We referred the GRU implementation from: https://github.com/cydonia99/rnn_variants_tensorflow 

This code can be run with Python 3 and Tensorflow v 1.4

* Question Answering:  
The original implementation can be found at: https://github.com/allenai/bi-att-flow

This code requires Tensorflow v 1.1 or higher on the dev branch, so `git checkout dev` before running the code. It can be run with Python 3.

* Dependency Parsing:  
The original implementation can be found at: https://github.com/chantera/biaffineparser

The code can be run with Python 3.

Additional instructions about data processing and installing dependencies can be found in the README of the mentioned repositories.

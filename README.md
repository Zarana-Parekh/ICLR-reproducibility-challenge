# ICLR-reproducibility-challenge
Code modifications for ICLR Reproducibility Challenge

# Update the code
`mv rnn_cell_impl.py /usr/local/lib/python3.6/site-packages/tensorflow/python/ops/`

`mv n_step_lstm.py /usr/local/lib/python3.6/site-packages/chainer/functions/connection`

`mv lstm.py /usr/local/lib/python3.6/site-packages/chainer/functions/activation`

# Running the experiments
There are three different experiments, some of the experiments require different Tensorflow versions so it is suggested that each experiment be run in a separate virutal environment in order to avoid having version issues.

More details have been given in the directory for each task.

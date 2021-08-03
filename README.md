# rbm-dbn-emnist
Deep belief network (DBN) implementation and analysis on EMNIST dataset using Google Colab.

The DBN class model has been adapted from Matlab source code provided by Computational Cognitive Neuroscience Lab, from University of Padova (ccnl.psy.unipd.it).

To run the application just upload the EMNIST dataset in the 'home' directory of Google COLAB environment and run all the cells.
In case a different location configuration is required, just edit the run configuration section in the jupyter notebook, where fname and datasetname variables are initialized to define dataset path files.

Hyperparameters of the Deep belief network can be changed in the same run configuration section, the developed code allows allows sequence run of different DBN models by defining list of model hyperparameter configurations.

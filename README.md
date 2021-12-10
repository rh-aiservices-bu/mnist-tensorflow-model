# Interactive MNIST Demo
### Or: 0 to AI in 2 notebooks

This set of notebooks takes you through a gentle introduction to one of the most basic AI problems, the MNIST dataset

MNIST is a dataset of 60,000 handwritten digits, which is used as input to train an AI. The AI learns the relationship between the pixel values, the arrangement, and the digit. The AI then is able to label arbitrary handwritten digits.

This will require:
  * Red Hat OpenShift Data Science managed service
  * Python 3
  * The ability to untar .tar.gz files
  * Access to the internet for pip installs

You will need to unzip the Resources.tar.gz file which contains the MNIST dataset.  Open a Terminal window from the Launcher and type the following command into the terminal window:

tar xvzf Resources.tar.gz


Once you have cloned the mnist-tensorflow-model github repo into your JupyterLab session, follow the notebooks in numbered order:
  * 00-MNIST-S3-Download.ipynb:  Covers the basics of downloading the MNIST data set from S3.
  * 01-MNIST-Data-Exploration:   Covers some of the basics about data exploration and gives an intro to the MNIST dataset
  * 02-MNIST-TensorFlow:         Covers creating the model, what layers are important, why to use certain ones, and training, testing, and saving the 
                                 model.




## Introductory Tutorial on scikit-learn (NLP track)

This tutorial is intended for people:

* who have little to no knowledge of scikit-learn
* who have some knowledge of Python
* who are interested in NLP and ML

### Prerequisites:
1. Some knowledge of Python
2. Basic understanding of NLP and ML

### Instructions:

#### 1. Install Anaconda and Jupyter
To avoid some complicated issues regarding Python dependencies or permission problems
related to your local environment, I highly recommend installing [Anaconda](https://www.continuum.io/downloads).
It is an isolated Python environment designed for data science, which includes various
packages that we will need, including Jupyter. Furthermore, it will make installing
scikit-learn a lot less painful.

If you insist using your existing Python environment instead of Anaconda, you may install
Jupyter using ``pip``.
```
pip install jupyter
```

#### 2. Install scikit-learn
If you have Anaconda installed, you can install scikit-learn as follows:
```
conda install scikit-learn
```

If you are not using Anaconda, make sure that you have the latests SciPy and NumPy installed,
and then run:
```
pip install -U scikit-learn
```

For this tutorial, please also make sure that you have Pandas installed, if you are not
using Anaconda.
```
pip install -U pandas
```

For more details about installation of scikit-learn, go [here](http://scikit-learn.org/stable/install.html).

#### 3. Download this repo
Now, we need download the tutorials from this repo, and start up the notebook server.
```
git clone https://github.com/justinsowhat/scikit-learn-nlp-tutorial.git
cd scikit-learn-nlp-tutorial
jupyter notebook
```
This should open up your default browser, and show you a list of files under this directory.
Click on a ``.ipynb`` file to start up a tutorial.
Within a tutorial, each block of code is runnable. You can select a block of code, and click on the run button
on the ribbon, and the Python kernal will run the code.



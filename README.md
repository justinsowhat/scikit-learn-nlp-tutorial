## scikit-learn for NLP tutorials

This is a two-part tutorial on scikit-learn with a focus on NLP.

Topics included:

* loading data
* simple preprocessing
* training (supervised, semi-supervised, and unsupervised)
* evaluation
* feature engineering
* custom transformer
* pipeline
* feature union

These tutorials are intended for people:

* who have little to no knowledge of scikit-learn
* who have some knowledge of Python
* who are interested in NLP and ML

### Prerequisites:
1. Some knowledge of Python
2. Basic understanding of NLP and ML
3. Ability to look up unfamiliar concepts in Wikipedia

### Instructions:

#### 1. Install Dependencies

##### a. If you are using Anaconda
To avoid some complicated issues regarding Python dependencies or permission problems
related to your local environment, I highly recommend installing [Anaconda](https://www.continuum.io/downloads).
It is an isolated Python environment designed for data science, which includes various
packages that we will need, including Jupyter. Furthermore, it will make installing
scikit-learn a lot less painful.

After installing Anaconda, you can install scikit-learn as follows:
```
conda install scikit-learn
```

##### b. If you are using your existing Python environment
If you wish to use your existing Python environment instead of Anaconda, you may install
all the dependencies needed in this tutorial using ``pip``. To make everyone's life somewhat easier,
use the ``requirements.txt`` file provided in my repo.

```
git clone https://github.com/justinsowhat/scikit-learn-nlp-tutorial.git
cd scikit-learn-nlp-tutorial
pip install -r requirements.txt
```


#### 3. Download this repo
Now, you need to clone this repo if you haven't, and start up the notebook server.
```
git clone https://github.com/justinsowhat/scikit-learn-nlp-tutorial.git
cd scikit-learn-nlp-tutorial
jupyter notebook
```
This should open up your default browser, and show you a list of files under this directory.
Click on a ``.ipynb`` file to start up a tutorial. If it doesn't, open your browser, and go to
http://localhost:8888/.


Within a tutorial, each block of code is runnable. You can select a block of code, and click on the run button
on the ribbon, and the Python kernal will run the code.

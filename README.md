# Dato Training Notebooks

Some notebooks used by in Dato's GraphLab Create Trainings.

### The Data

The data for these notebooks consists of a recommender systems dataset which can be downloaded from these addresses. It should be placed in the same folder as the training IPython Notebooks.

* [https://s3.amazonaws.com/dato-datasets/dato-training/review.csv.gz](https://s3.amazonaws.com/dato-datasets/dato-training/review.csv.gz) (80.4 MB)

Business reviews written by users. Each review also includes a rating (ranging from 1 to 5 stars). As such, it can be used for training a recommender system, as it describes user-item relationships (user-business in this case) along with a target variable (the stars rating).

* [https://s3.amazonaws.com/dato-datasets/dato-training/business.csv.gz](https://s3.amazonaws.com/dato-datasets/dato-training/business.csv.gz) (640.2 KB)

Side features describing the businesses appearing in the reviews.

* [https://s3.amazonaws.com/dato-datasets/dato-training/user.csv.gz](https://s3.amazonaws.com/dato-datasets/dato-training/user.csv.gz) (1.1 MB)

Side features describing the users who wrote the reviews.

### The Notebooks

Below are the currently available notebooks. More notebooks will be added soon!

[Basic Training](Dato Basic Training.ipynb) - tabular data maniuplation using SFrames, graph analytics using SFrame and our PageRank toolkit, and some predictive modelling using our recommenders toolkit.

[Advanced Exercise](Dato Exercise.ipynb) - an exercise consisting of re-creating the backend of our [Pathyways Recommender demo](http://pathways-demo.herokuapp.com/). This exercise is harder than the ones given in the training, and can be considered a 'home work' for enthusiasts.

### Going Further

More notebooks on many different topics can be found in [the notebook gallery](https://www.dato.com/learn/gallery).

More information about our toolkits can be found in our [API documentations](https://dato.com/products/create/docs/).

Users willing to learn GraphLab Create in its entirely should [go through our user guide](https://dato.com/learn/userguide/).


# Music-Genre-Prediction

The goal of this project is to build and critically analyse some supervised Machine Learning algorithms, to automatically identify the genre of a song on the basis of its audio, metadata and textual features. That is, given a list of songs, your job is to implement one or more Machine Learning model(s), train them using the training dataset, and evaluate using the test validation and test dataset.
This project aims to reinforce the largely theoretical Machine Learning concepts around models, data, and evaluation covered in the lectures, by applying them to an open-ended problem.

## Dataset

train_features.csv: Contains features of 7678 training instances.
train_labels.csv: Contains a single genre label for each training instance
valid_features.csv: Contains features of 450 validation instances.
valid_labels.csv: Contains a single genre label for each validation instance.
test_features.csv: Contains features of 428 test instances.

## Running

Split data sets into a training set and a hold-out test set

```
split_data()
```

Build Naive Bayes and K-NN classifiers from the training data

```
train()
```

Use a trained model to predict a class for the test data

```
predict()
```

Output the accuracy of your classifiers, or sufficient information so that it can be easily calculated by hand

```
evaluate()
```

## Running
Download [Jupyter Notebook](https://jupyter.org/) - Open the ipynb file with it.

## Built With
* [Jupyter Notebook](https://jupyter.org/) - Running Analysis
* [Python](https://www.python.org/) - Source code

## Authors

* **Haichao Song** - *University of Melbourne*

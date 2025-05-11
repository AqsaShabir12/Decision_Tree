# Decision Tree Classifier from Scratch 

This repository provides a clear implementation of a **Decision Tree Classifier** built entirely from scratch using **NumPy** and Python. It demonstrates how a decision tree learns to classify data by splitting based on features and thresholds using **information gain** and **entropy**.

The model is tested on the **Breast Cancer Wisconsin Dataset** from `scikit-learn`.

---

## File Structure

- **DecisionTree.py**  
  Contains the full implementation of the `DecisionTree` class with methods for splitting, calculating entropy, information gain, tree construction, and prediction.

- **main.py** 
  Loads the dataset, trains the classifier, predicts on the test set, and prints the classification accuracy.

---

## Requirements

Install the necessary packages with:

```bash
pip install numpy scikit-learn

```

## How to Run
Simply execute the script in your terminal:
```bash
python train.py
```
This will:

- Load the Breast Cancer dataset from scikit-learn
- Split it into training and testing sets
- Train a decision tree with a specified max_depth
- Make predictions on the test set
- Output the classification accuracy

## Dataset

The dataset used is the [Breast Cancer Wisconsin Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) provided by scikit-learn. It consists of 30 numerical features computed from digitized images of fine needle aspirates (FNA) of breast masses.


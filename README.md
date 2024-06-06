# credit-risk-classification

Jupyter notebook: https://github.com/redpandata19/credit-risk-classification/blob/main/credit_risk_classification.ipynb

Module 20 challenge, UNC Bootcamp. Background:
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Dependencies: 
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import confusion_matrix, classification_report

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression

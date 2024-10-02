# FraudDetection

This repository is dedicated to developing a Python project using machine learning algorithms to detect fraud.


## Technologies Used
- Python
- Pandas
- Scikit-learn
- NumPy
- Seaborn (for data visualization)

## Dataset
The dataset used in this project is the "Credit Card Fraud Detection" dataset, which is stored in a CSV file. The dataset contains transaction details labeled as either fraudulent or not.

M. L. G. ULB. (2019). Credit Card Fraud Detection. Kaggle. https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


### Loading the Dataset
To load the dataset, use the following code snippet:

```python
import pandas as pd

# Read the dataset (.CSV) file and load its contents into a DataFrame
df = pd.read_csv('/content/drive/MyDrive/datasets/creditcard.csv')

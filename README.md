# Machine Learning Income Predictor
Final project for UCI's Master of Computer Science program's CS 273P: Machine Learning and Data Mining class that uses machine learning to analyze a data set and predict a person's income
## Developed By
Harry Pham and Keith Tachibana
## Dataset
https://archive.ics.uci.edu/ml/datasets/adult
## Development
#### System Requirements
|     Requirement   |      Version     |
|-------------------|-----------------:|
| Jupyter Notebook  |  5.5.0 or higher |
| Numpy             |  1.15 or higher  |  
| Pandas            | 0.24.0 or higher |
| Python            |  3.6 or higher   |
#### Getting Started
1. Import the provided data_loader, which depends on your project's source root directory
  `import data_loader` or `from . import data_loader`
2. Load the training data using said data_loader
- __**data_loader**.***load_train_data***(*train_file_path*, *valid_rate*=0.1, *is_df*=True)__

- _INPUT:_
- ***train_file_path***: training file path of 'adult.data'
- ***valid_rate***: validation data rate (0 - 1), 0.1 by default
- ***is_df***: whether or not returned objects are pandas.DataFrame, True by default

- _OUTPUT:_
- ***train_features***: training feature 2D-array (numpy.ndarray, str and int columns)
- ***train_labels***: training label array (numpy.ndarray)
- ***valid_features***: validation feature 2D-array (numpy.ndarray, str and int columns)
- ***valid_labels***: validation label array (numpy.ndarray)
3. Load the testing data using said data_loader
- __**data_loader**.***load_test_data***(*test_file_path*, *is_df*=True)__

- _INPUT:_
- ***test_file_path***: test file path of 'adult.test'
- ***is_df***: whether or not returned objects are pandas.DataFrame, True by default

- _OUTPUT:_
- -***test_features***: test feature 2D-array (numpy.ndarray, str and int columns)
- -***test_labels***: test label array (numpy.ndarray)

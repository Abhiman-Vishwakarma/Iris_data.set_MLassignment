_Iris Dataset Exploration_

_Step 1: Import Necessary Libraries_

- Import the required libraries:
    - `pandas` for data manipulation and analysis
    - `load_iris` from scikit-learn for loading the Iris dataset

_Code:_
```
import pandas as pd
from sklearn.datasets import load_iris
```

_Step 2: Load the Iris Dataset_

- Load the Iris dataset using `load_iris`
- Convert the dataset into a Pandas DataFrame `iris_df` with feature names as columns

_Code:_
```
iris = load_iris()
iris_df = pd.DataFrame(data=iris.data, columns=iris.feature_names)
```

_Step 3: Display the First Five Rows_

- Print the first five rows of the dataset using `head()`

_Code:_
```
print("First five rows of the dataset:")
print(iris_df.head())
```

_Step 4: Display the Shape of the Dataset_

- Print the shape of the dataset (number of rows and columns) using `shape`

_Code:_
```
print("\nShape of the dataset:")
print(iris_df.shape)
```

_Step 5: Display Summary Statistics_

- Print summary statistics (mean, std, min, 25%, 50%, 75%, max) for each feature using `describe()`

_Code:_
```
print("\nSummary statistics of the dataset:")
print(iris_df.describe())
```

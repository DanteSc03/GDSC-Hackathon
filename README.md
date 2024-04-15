# [Google Developer Student Club Navarra](https://www.linkedin.com/company/gdsc-unav/mycompany/) Hackathon 2024

This hackathon was designed to identify the segmentation of future clients of Tesla based on past and current clients. This was created utilizing the Scikit-Learn machine learning models. You can access their [Github](https://github.com/scikit-learn/scikit-learn) or their [website](https://scikit-learn.org/stable/#) for more ML methods or documentation. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following packages.

```bash
pip install seaborn 
pip install scikit-learn 
pip install pandas

```

## Usage

```python
# Make sure to import all of the following libraries to ensure functionality
import csv
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression, LogisticRegression
from sklearn.preprocessing import LabelEncoder, StandardScaler, MinMaxScaler
from sklearn.impute import SimpleImputer
from sklearn.pipeline import Pipeline
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
  
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Contact

[Dante Mathieu Schrantz](https://www.linkedin.com/in/dante-m-schrantz/)

[Miguel Diaz Perez de Juan](https://www.linkedin.com/in/migueldiazperezdejuan/)

## Contributing

Contributions to improve this tool are welcome. Feel free to fork this repository and submit your pull requests.

## License

[MIT License](LICENSE.md)

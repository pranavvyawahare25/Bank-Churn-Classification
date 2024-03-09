# Bank-Churn-Classification

# Bank Churn Classification

## Overview
This repository contains code for predicting customer churn in a bank using machine learning techniques. Customer churn refers to the phenomenon where customers stop doing business with a company. Predicting churn is crucial for businesses, especially in industries with high competition, such as banking, as it allows proactive measures to retain customers.

## Dataset
The dataset used in this project is a fictional dataset representing customers of a bank. It contains various features such as customer demographics, account information, transaction history, etc. The target variable is 'Churn', indicating whether a customer has churned or not.

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/pranavvyawahare25/bank-churn-classification.git
    ```
2. Install dependencies:
    ```
    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns 
    import warnings

    ```



## Model Performance
- Include details about the model's performance metrics, such as accuracy, precision, recall, F1-score, etc.
  
  Model-Name	                Accuracy	       AUC	         F1-Score
  
0.	DecisionTreeClassifier	    80.006463	    70.431959	     53.069739
1. 	RandomForestClassifier	    85.845570	    87.133568	     61.315964
2. 	GradientBoostingClassifier	86.481792	    88.792851	     62.489492
3.  ExtraTreesClassifier	    85.310335	    86.395071	     60.263345
4.  AdaBoostClassifier	        86.075822	    87.944320	     61.360834
5.  LogisticRegression	        83.258266	    81.294726	     48.601724
6.  XGBClassifier	            86.352528	    88.588906	     63.255207




  
## Contributing
Contributions to improve the code or add new features are welcome. Please follow the standard GitHub workflow:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/new-feature`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.


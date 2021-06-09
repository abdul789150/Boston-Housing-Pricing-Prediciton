# Boston-Housing-Pricing-Prediciton

## Dataset Explanation
This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It was obtained from the StatLib archive (http://lib.stat.cmu.edu/datasets/boston), and has been used extensively throughout the literature to benchmark algorithms. However, these comparisons were primarily done outside of Delve and are thus somewhat suspect. The dataset is small in size with only 506 cases.

There are 14 attributes in each case of the dataset. They are:
- **CRIM** - per capita crime rate by town
- **ZN** - proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS** - proportion of non-retail business acres per town.
- **CHAS** - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **NOX** - nitric oxides concentration (parts per 10 million)
- **RM** - average number of rooms per dwelling
- **AGE** - proportion of owner-occupied units built prior to 1940
- **DIS** - weighted distances to five Boston employment centres
- **RAD** - index of accessibility to radial highways
- **TAX** - full-value property-tax rate per 10,000 USD
- **PTRATIO** - pupil-teacher ratio by town
- **B** - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- **LSTAT** - % lower status of the population
- **MEDV** - Median value of owner-occupied homes in 1000's USD

In the above mentioned 14 attributes, `MEDV` is a target or label attribute and other 13 attributes are considered as `features`. 

## Required Libraries

- **Numpy** - Used for matrix computation and statistical work.
- **Pandas** - Used for reaading and savind datasets, and it is also used in some other computational tasks.
- **Seaborn** - Used for visualizations
- **Matplotlib** - Used for visualizations
- **Sklearn** - Used for ML models, data scalling and loading boston dataset

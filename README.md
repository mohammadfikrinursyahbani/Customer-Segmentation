# Customer-Segmentation
## Dataset Description
| Variable | Data Type | Range | Description |
|------|------|-----------|-----------|
| ID | Numerical   | Integer   | Shows a unique identificator of a customer |
| Sex | Categorical   | {0,1}   |Biological sex (gender) of a customer. In this dataset there are only 2 different options. 0 = Male, 1= = Female |
| Marital Status | Categorical   | {0,1}  | Marital status of a customer. 0 = Single, 1 = Non-single (divorced / separated / married / widowed) |
| Age | Numerical   | Integer  | The age of the customer in years, calculated as current year minus the year of birth of the customer at the time of creation of the dataset. 18 = Min value (the lowest age observed in the dataset). 76 = Max value (the highest age observed in the dataset) |
| Education | Categorical   | {0,1,2,3}  |Level of education of the customer. 0 = Other/Unknown, 1 = High School, 2 = University, 3 = Graduate School |
| Income | Numerical   | Real  | Self-reported annual income in US dollars of the customer |
| Occupation | Categorical   | {0,1,2}  | Category of occupation of the customer. 0 = Unemployed/Unskilled, 1 = Skilled employee/official, 2 = management/self-employed/high qualified employee/officer |
| Settlement Size | Categorical   | {0,1,2}  |The size of the city that the customer lives in. 0 = Small city, 1 = Mid-sized city, 2 = big city |
## Result Segmentation
- Cluster 0 : Single + Medium/big city + Male + Employed (employee or self-employed)
- Cluster 1 : Non-single + Female + small city + unemployed atau employees ( Ada sangat sedikit kasus di medium / big city)
- Cluster 2 : Non-Single + Female + medium/large city + management/self-employed
- Cluster 3 : Single + Small city + Male + Employed
- Cluster 4 : Non-Single + Male
- Cluster 5 : Single + Female + Small city (Ada sangat sedikit kasus medium sized city/big city)
## Dependencies
This lab requires **Python 3.10.11** and the following Python libraries installed:
* Basic Libraries: [Pandas](https://pandas.pydata.org), [NumPy](http://www.numpy.org)
* Visualization Libraries: [Matplotlib](http://matplotlib.org), [Seaborn](https://seaborn.pydata.org)
* Machine Learning Libraries: [Scikit-Learn](https://scikit-learn.org)

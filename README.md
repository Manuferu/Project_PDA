# Housing price in County Limerick
Repository to host the final project for Programming for Data Analytics
#### Author: Manuel Fernandez 
#### University: Galway-Mayo Institute of Technology (GMIT)

## Introduction

Housing price in Ireland, has has experienced a ramping up on their prices in the recent years and it is expected to continue like that in a forseen future. But as an investor, how many years will keep the price going up? which variables could influence the price even within the same city?. What an investor will face off when it comes to calculate the worth after an investment?

## Methodology
this project has been presented using Jupyter notebook to explain and output the data. The notebook is broken down as follows:

### Datasets creation:

The creation of the datasets is a mix of random data generated using different numpy random functions and existing data, captured from Central Office of Statistics (CSO). That is has been done to hit the target proposed by the project requirements to have at least 100 data entries per variable. When creating the random data, it has been tried to limit the low and high values as well as the distribution with more or less "logical" values even though in some cases it has been hard to reach out this.

### Join Dataset

After the datasets are created, it has been taken relevant information of each of those and put them all in one dataset. Pairplot has been generated in order to have a view of the distribution of each of the variables and have information about correlation.

### Precition model

Once the dataset is generated, a prediction model has been created using sklearn's Linear regression. The user is asked to introduce six variables and the model outputs the predicted price taking into account the variables introduced.


## Information within the folder:

-house_price.ipynb : Jupyter notebook file with all the information

-EDA57.20201230T121257.csv : School information from CSO (1)

-HPA02.20210101T190157.csv : Property price from CSO (1)

-IIA01.20201230T121251.csv : Gross income from CSO (1)

-MUM01.20201230T121228.csv : unemployment information from CSO (1)


### Statement

This is an exercise for an specific subject. Even though it uses real data, mostly of the data is generated randomly, so it doesn't match the reality. 

## References
(1) Central Statistics Office : (https://www.cso.ie/en/index.html)

(2) Limerick.ie : https://www.limerick.ie/sites/default/files/media/documents/2018-07/Economic%20Profiling%20Report%20for%20Limerick%20City%20and%20County.pdf

(3) Limerick.ie (Population Growth) : https://www.limerick.ie/business/growing-limerick/facts-and-figures/limericks-recent-economic-growth

(4) Towards data Science : (Linear regression) https://towardsdatascience.com/linear-regression-in-6-lines-of-python-5e1d0cd05b8d

(5) Limerick.ie (Unemployement rate) https://www.limerick.ie/business/growing-limerick/facts-and-figures/limericks-recent-economic-growth#:~:text=The%20CSO's%20Labour%20Force%20Survey,of%205.7%25%20in%20Q1%202018.

(6) Limerick.ie (investment): https://www.limerick.ie/business/growing-limerick/facts-and-figures/limericks-recent-economic-growth#:~:text=The%20CSO's%20Labour%20Force%20Survey,of%205.7%25%20in%20Q1%20

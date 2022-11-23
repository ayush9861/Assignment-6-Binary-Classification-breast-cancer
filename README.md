# Assignment-6-Binary-Classification-Breast-Cancer

### What is Binary Classification of Breast Cancer?

Breast Cancer is a cancer that devlops from breast cancer. Breast Cancer may include lumps in breast, a change in breast shape, dimpling of the skin, fluid coming from th nipples etc. Breast cancer may be devloped due to lack of physcical excercise, alcoholism, hormon replacement therapy during menopause, having child late in life or not at all.

### Problem Statement:

The Problem in hand is a binay classification in which we are going to compile the data from the data.csv file and try to analyze the result. This binary classification cointains a lot of characteristics of tissue culture like radius,smoothness, texture, smoothness etc. While the output is binary.

In, this project our aim is to try to understand the features, execute some strategies for feature reduction, apply a binary classification algorithm until performance saturates.

### About Dataset:

Here, for this project we have used a file named Data.csv. In this file we have 569 rows and 33 columns. Out of the 33 colums the first two colums includes Id and diagnosis. Some of the top ten features of are:

* Radius
* Concavity
* Texture
* Smoothness
* Symmetry
* compactness
* concave points
* Area
* Fractal dimension
* Perimeter













## Applications Used:

**Python: 3.10.2**

**Jyputer Notebook: 6.1.5**


## Libraries Used:

**Numpy: 1.19.0** 

**Matplotlib: 3.6.2**

**Seaborn: 0.12**

**Pandas: 1.5.1**

## Sample Data Taken:

**data.csv**

## Operations:

In this step we have imported all the libraries which we are going to use for conducting different operations with the data.csv file. After, importing all the libraries we have used the pandas **read_csv()** function to read the data.csv file and used the pandas **head()** and **describe()** function to return the first n rows based on position and describe to return the description of the data in the DataFrame.


![](https://i.imgur.com/zdNmC9B.png)


Here, in this step we have we are using **isnull()** method pf pandas library to return a dataframe object where all the values are replaced with a Boolen value True for Null and otherwise False. After, conducting this operation we have use the **sum()** function to add all values in each column and return the sum of each column.


![](https://i.imgur.com/ZmBPUn2.png)


Here, in this step I have used **Seaborn** countplot function to plot he graph of labels and count.


![](https://i.imgur.com/ODTYCMb.png)


Here, in this step we have used the pandas drop function to remove the specified row and column and we have also used the **Sklearn's** MinMaxScaler to scale and transform the data present in the variable X.


![](https://i.imgur.com/K6mrYO7.png)


Here, in this step we have **Keras** Sequential library to implement our algorithm.


![](https://i.imgur.com/NGAjXek.png)


Here, in this step we are using **Metplotlib** plot function to build a graph for better data visualization.


![](https://i.imgur.com/BvT9TS5.png)


Here, is the outcome of the graphs.


![](https://i.imgur.com/IbreTBW.png)


Using, the **Sklearn** Confusion_Matrix function we, have genertaed a heat map showing the outcome of our operations.


![](https://i.imgur.com/3zUwWAc.png)




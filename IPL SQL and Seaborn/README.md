The **SQLite Database** used in this EDA is related to  ***Indian Premier League***  of  Cricket with 577 matches, players & teams attributes from **seasons 2008 to 2016.** The database has 22 tables storing data related to measurements of various attributes of the game cricket. 

I used the ***sqlite3*** library of python to connect to the database and ***pandas*** to read SQL query or database table into a DataFrame  and got the required results and used the ***seaborn*** and ***matplotlib*** data visualization libraries to visualize the data. 

The Database Diagram is given below.
![](https://i.imgur.com/327NVKH.png)

File overview:

* `ipl-sql-and-seaborn.ipynb` - a Jupyter notebook that contains the code to the SQL queries and visualizations on the IPL sqlite database.

A sample visualization done in the project 
![](https://github.com/RamaTadi/Data-Science-Projects/blob/main/IPL%20SQL%20and%20Seaborn/Visualizations/__results___38_0.png?raw=true)

## Setup

### Installation 

The project is done online on kaggle notebook. 
To to this one needs

* Kaggle Notebook or Jupyter Notebook
* Python 3.7.12 + 
* Python packages
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn 
    * Sqlite3

### Data 
The data used for this project can be downloaded from the kaggle [here](https://www.kaggle.com/datasets/harsha547/ipldatabase) 

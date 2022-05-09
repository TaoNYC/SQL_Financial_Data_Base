# SQL for Financial Data Base

This is a Python application allowing users to build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF 

The application works by extracting data from etf.db using sqlite, use hvplot to show daily return, cumulative return and conditionally select certain data points and also analyze the portfolio as a whole. 
 

 
---

## Technologies

This project leverages python 3.7 +, pandas, nsqlalchemyumpy, pathlib, hvplot


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install pandas
  pip install sqlalchemy

```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

Step 1: run etf_analyzer.ipynb
```python
python etf_analyzer.ipynb
```
Step 2: Create an interactive visualization with hvplot to plot the daily returns for PYPL.


<img width="701" alt="image" src="https://user-images.githubusercontent.com/99616004/167323387-51f16d51-a603-442c-8935-4ad76a534dd0.png">

Step 3: Create an interactive visaulization with hvplot to plot the cumulative returns for PYPL.


<img width="695" alt="image" src="https://user-images.githubusercontent.com/99616004/167323432-4bba7bd5-1f7f-4d20-b3a7-306fc0f8649b.png">



Step 4: Using hvplot, create an interactive line plot that visualizes the ETF portfolios cumulative return values.


<img width="696" alt="image" src="https://user-images.githubusercontent.com/99616004/167323477-cac18453-e81f-4871-a5c3-13ff434b8219.png">

Step 5: Take a screen recording or screenshots to show how the web application appears when using Voilà. Include the recording or screenshots in the `README.md` file for your GitHub repository.

<img width="1412" alt="image" src="https://user-images.githubusercontent.com/99616004/167323566-22d2238d-2a9e-4db5-b581-0c0e1efb6086.png">



Conclution:  

SQL data base turns out to be a very useful tool to store, read, manipulate and visulize large quantity of data. 



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp

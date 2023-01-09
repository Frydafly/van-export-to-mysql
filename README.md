# About

These SQL scripts run code that updates the data in our MySQL server from the voter file

# serverupdate instructions


Use jupyter notebook if the csv file is less than 50,000 rows

If more than these rows, then make a copy of the notebook, convert into python using nbconvert. 

If you do not have nbconvert, then 

`pip install nbconvert`

then you can run the below!

``` 
ipython nbconvert CHConvert.ipynb --to python
```

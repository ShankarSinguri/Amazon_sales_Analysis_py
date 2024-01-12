# Python_Amazon_Sales_Analysis

## Overview:
This project provides a comprehensive analysis of Amazon sales data, allowing users to gain valuable insights into sales trends based on various parameters such as product category,size,order status,amount,state-wise and city-wise distribution of the sales.

## Table of Content:
1.[Introduction](#introduction)

2.[Features](#features)

3.[Data](#data)

4.[EDA](#eda)

5.[Observations](#observations)

6.[Analysis-Report](#analysis-report)

## Introduction:

Understanding sales patterns is crucial for business success. This project aims to assist users in analyzing Amazon sales data, providing a deeper understanding of how different factors contribute to overall sales performance.
## Features:
Important features considerd for analysis are:
- Order Id
- Date
- Status
- Fullfilment
- Category
- Size
- Courier status
- Quantity
- Amounnt
- Ship-state
- Ship-city
- etc

## Data:
The primary dataset used for this analysis is the "Amazon sale report.csv" file.This data set contains sample Amazon sales data and the analysis is done using this primary data set.

## EDA:
- Analysis

The analysis is performed using Python and popular data analysis libraries such as Pandas, Matplotlib, and Seaborn. The Jupyter notebooks in the notebooks directory provide detailed step-by-step analyses for each feature.

Include some interesting code/features worked with
````python

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
ax=sns.countplot(data=df,x='Status')
# plt.figure(figsize=(20,5))
ax.bar_label(ax.containers[0])
plt.xticks(rotation=90)
plt.show()
`````
## Observations:

- In order status : majority of the orders are deliverd to the customers.
- Tshirts are the most selling items followed by Shirts and Blazzers.
- Size:M,L,XL are top seling sizes.

## Analysis Report:

The Data analysis reveals that buissness has significant customer base in Maharashtra,Uttarpradesh,Karnataka and experinces high demand in tshirts with M and L sizes are most prefferd sizes among the customers.  





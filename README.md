# Supermarket-Sales-Analysis
## Nasa Supermarket Analysis
## Table of Content

- [Problem Statement](problem-statement)
- [Skills / Concepts demonstrated](skills-concepts-demonstrated)
- [Data Analysis](data-analysis)

## Introduction
***
This is a python and SQL project on an imaginary supermarket called **Nasa Supermarket**.
the project objectives is to analyze and glean insight to answer critical questions and help the supermarket make data driven decisions.

**_Disclaimer_**:
All dataset and reports here do not represent any company, institution or state but just a dummy dataset to demonstrate the power of python and SQL in data analysis.

## Problem Statement

1. What is the overall sales trend?
1. Which product in the current quarter has the highest impact in income?
2. What is the worth in Naira of the total products available?
3. What are the sales peak period?

## Skills / Concepts demonstrated

The following python and Sql features were incorporated
- pandas - import dataset
- numpy - manipulate values
- matplotlib - plot visualizations
- GitHub - creating reports

## Data Analysis
Some interesting codes or features worked with

```python
sales_df = pd.read_csv("C:/Users/Nasa/Databank Analysis/Dataframe/sales.csv")
```


```sql
select * from sales
```

```
sales.columns = [i.lower() for i in sales.columns]
```

## Visualization

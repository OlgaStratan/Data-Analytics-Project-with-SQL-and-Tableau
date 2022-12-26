# Nashville Housing (Data) Cleaning Project
In this project, I was using Microsoft SQL Server to clean [Nashville Housing dataset](https://github.com/AlexTheAnalyst/PortfolioProjects/blob/main/Nashville%20Housing%20Data%20for%20Data%20Cleaning.xlsx). The Dataset has more than 56,000 rows and 19 columns.

The following tasks were performed:
- Standardize date format
- Populate missing property address data
- Parsing long-formatted address into individual columns (Address, City, State)
- Standardize “Sold as Vacant” field (from Y/N to Yes and No)
- Remove Duplicates

## Overview of data
```
# Overview of the dataset

Select *
FROM portofolio.dbo.NashvilleHousing
```
**output:**
![Screenshot 2022-12-26 165338](https://user-images.githubusercontent.com/67650188/209565701-545a52a2-2bb1-413a-a61f-c18cd6b4b487.png)
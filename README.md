
# BzPlan Dembe 
BzPlan Dembe is a webapp that brigdes the gap between investors and small business enterprenuers. It provides a platform for enterprenuers to develop and share their business plans and finantial forecasts. It uses machine learning to rank the business plans and recomend them to investors.

## Table of Contents
* [Overview](#Overview)
* [Tech Stack](#Tech-Stack)
* [Setup and installation](#Setup-and-installation)
* [Data Model](#Data-Model)
* [Main Screen Flow](#Main-Screen-Flow)
* [Financial Statment](#Financial-Statments)
* [Future Features](#Future-Features)



## Overview
The BZPlan Dembe is a solution to provide access to funding for business ideas. This application would have the following key features:
* Allow for users to free submit and manage their business plans
* Allow for users to review other business plans
* Moderators and backend users can generate reports
* A recommendation engine can scan the business plans based on specified rules and present those plans to financial institutions or funding source. 



## Tech Stack
Data Wrangling: Pandas, Numpy , seaborn, matplotlib <br>
Framework: Flask <br>
Backend: Python, SQLAlchemy, PostgreSQL ,SciKit_Learn <br>
Frontend: Javascript , Jinja, HTML, CSS, Bootstrap <br>

## Setup and installation
On local machine, go to desired directory. Clone  repository:<br>
```python
$ git clone https://github.com/Claire56/HackDay
```
Create a virtual environment in the directory:<br>
```python
$ virtualenv env
```
Activate virtual environment:<br>
```python
$ source env/bin/activate
```
Install dependencies:<br>
```python
$ pip install -r requirements.txt 
```
Create database:<br>
```python
$python 
>>> flask db init db 
>>> flask db migrate
>>> flask db upgrade

run app 
$python server.py
```

## Data Model

![bizPlanDataModel](./docs/bizPlanDataModel.png)

## Main Screen Flow

### Structure
Defines the business structure

![Structure](./docs/1.Structure.png)

### Products for the business
Defines the products the business is producing or is planning to produce
![Products](./docs/2.Products.png)


## Marketing
Target and established markets. Advertising strategy and others
![Marketing](./docs/3.Marketing.png)


## SWOT
SWOT analysis
![SWOT](./docs/4.SWOT.png)


## Operational
Day-to-day ops, facilities and staffing

![Operational](./docs/5.Operational.png)


## Financial Details
Defines the business structure

![FinancialDetails](./docs/6.FinancialDetails.png)

### Financial Statments
Includes financial statments for cashflow forecasting

![FinancialStatments](./docs/7.FinancialStatements.png)

## Future Features

### Review Business
Listing selectable list of business plans

![ReviewBusinessCases](./docs/8.ReviewBusinessCases.png)

### Recommend Business Plans
Based on selected criteria recommend business plans to financial institution


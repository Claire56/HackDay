## How to Run Project
### create a virtualenv
$virtualenv env
### activate virtualenv
$source env/bin/activate
## install packages 
$pip3 install -r requirements.txt
### create database 
$python
>>> from project import db <br>
>>> db.create_all()
### run app
$python server.py


# Main Screen Flow

## Structure
Defines the business structure

![Structure](./docs/1.Structure.png)

## Products for the 
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

## Data Model


![bizPlanDataModel](./docs/bizPlanDataModel.png)

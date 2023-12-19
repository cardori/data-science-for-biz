# data-science-for-biz
Python and Jupyter notebook to address business problems, using Data Science.

The following project looks at the historical retail sales data, in this case from a subset of 45 Walmart stores, and the relationship to year (date), holidays, temperature, fuel price, consumer price index, and unemployment.<br>

The historical data covers sales from 2010-02-05 to 2012-11-01, in the file: **walmart.csv**.  

<div class="alert alert-block alert-info">
<font color='black'>
*Rubric:  Dataset included* 
</font>
</div>
The source of data file: https://www.kaggle.com/datasets/yasserh/walmart-dataset 

Within the raw file you will find the following fields:

* Store - the store number
* Date - the week of sales
* Weekly_Sales - sales for the given store
* Holiday_Flag - whether the week is a special holiday week 
    * 1 – Holiday week 
    * 0 – Non-holiday week
* Temperature - Temperature on the day of sale
* Fuel_Price - Cost of fuel in the region
* CPI – Prevailing consumer price index
* Unemployment - Prevailing unemployment rate
* Holiday Events:
    * Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
    * Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
    * Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
    * Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

Ideally, I would like to answer the following types of questions:

* Does weather (Temperature) impact weekly sales (Weekly_Sales)?
* Does Fuel Price (Fuel_Price) impacted weekly sales (Weekly_Sales)?
* What is the Store (1 - 45) that has the most Sales (sum of Weekly_Sales)?
* The data also has a flag for holiday (0 - not a holiday, 1 is a holiday)?  I want to see if that impacts the results.

## How to install locally

* create a local directory 
   * `mkdir ds_biz`

* change directory
   * `cd ds_biz`

* Download the git repository
  * `git clone https://github.com/cardori/data-science-for-biz.git`

* change directory
   * `cd data-science-for-biz/`

* Setup python virtual environment
  * `python3 -m venv env`

* Install python packages
   * `pip install -r requirements.txt`

* Run jupyter notebook locally
   * `jupyter notebook`

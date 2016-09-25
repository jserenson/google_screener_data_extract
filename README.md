google_screener_data_extract
===============================

version number: 0.0.1
author: Tan Kok Hua

Overview
--------

Retreive stock data from google finance screener

Installation / Usage
--------------------

To install use pip:

    $ pip install google_screener_data_extract


Or clone the repo:

    $ git clone https://github.com/spidezad/google_screener_data_extract.git
    $ python setup.py install
    
Contributing
------------

TBD

Example
-------
hh = GoogleStockDataExtract()
hh.target_exchange = 'NASDAQ'
hh.retrieve_all_stock_data()

print hh.result_google_ext_df.head()
hh.result_google_ext_df.to_csv(r'c:\data\temp.csv', index =False) #any save file name
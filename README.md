# Yahoo Finance Python API

* This API Supports to retrieve data especially works for NSE/BSE stocks.
* Also can Retrieve Intraday 1min gradualar Data.

# Python Installation:
* Command for installation: 'pip3 install raptorfinance'

## Usage

This command returns a dataframe which can be further modified to add new columns , exported to excel etc
* from raptorfinance import RaptorFinance
``` python
hdfc = RaptorFinance('HDFC.NS', result_range='1mo', interval='15m', dropna='True').result
```


## Installation

``` bash
git clone https://github.com/swaroop9ai9/Fintech/raptor_finance_api.git
cd raptor finance
python setup.py install
```

### Requirements

- Pandas
- Request

### Note

Make sure to use TICKER symbol from yahoo finance website
https://in.finance.yahoo.com/ 

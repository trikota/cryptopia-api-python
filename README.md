# Cryptopia python API by CC Tech
Alessandro Sanino AKA The Bot Guy (thebotguy@usa.com)

Disclaimer: This does not guarantee profit and you can still lose money if your
sell order does not fill. (A sell order set too high may not be filled)

It is all dependent on the volume of the pump and how much you are intending to liquidate.
Build up your profits gradually and do not be too greedy, else you can be caught holding
the bag. Do proper preparation to know how much to use and where to set your buy/sell at!

This program is for educational purposes only and is provided AS IS and without warranty.
Please check LICENSE file.

# Overview
This wrapper provides a friendly way to call Cryptopia API from a Python 2.7 script. Requires requests 2.8.1

## Usage
Just import it and use it.

``` python
from cryptopia_api import Api

#later...
api_wrapper = Api(MY_PUBLIC_KEY, MY_SECRET_KEY)

#call a request to the api, like balance in BTC...
balance, error = api_wrapper.get_balance('BTC')
if error is not None:
    #handle error
    print 'ERROR: %s' % error
else:
    #ok
    print 'Request successfull. Balance in BTC = %f' % balance
```

Check cryptopia API docs for the parameters of each call: a more detailed wiki will be added here soon!
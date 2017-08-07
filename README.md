# Cryptopia PUMP BOT by cc-tech
The Bot Guy <thebotguy@usa.com>

Disclaimer: This does not guarantee profit and you can still lose money if your
sell order does not fill. (A sell order set too high may not be filled)

It is all dependent on the volume of the pump and how much you are intending to liquidate.
Build up your profits gradually and do not be too greedy, else you can be caught holding
the bag. Do proper preparation to know how much to use and where to set your buy/sell at!

## Calling the Bot
You have to create a secrets.json file with your public and secret key
like this:

``` javascript
{
    "public" : "YOUR_PUBLIC_KEY",
    "secret" : "YOUR_PRIVATE_KEY"
}
```

``` sh
$ python cryptopia_pump_script.py
```

## Requirements
`requests v.2.18.1` or greater

Or just use `pip`:
``` bash
$ pip install -r $REPO_DIR/requirements.txt
```

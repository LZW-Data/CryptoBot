[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LZW-Data/CryptoBot/HEAD)

# CryptoBot
Experimental exploration in interacting with a binance API and utilising it to explore algorithmic and AI (Machine Learning) trading.

## Setup
To use access the Binance API you will need to create an account and retrieve the API keys. You can then put these in a config.py file of the form:

    api_key = 'YOUR_API_KEY'
    api_secret = 'YOUR_SERET_API_KEY'

These are then accessed in the main body like this:

    import config
  
      # Example line displaying usage
       api_key, api_secret = config.api_key, config.api_secret 

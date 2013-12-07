# Coinbase CLI Tool

## Dependencies

[jq](http://stedolan.github.io/jq/)

    brew install jq

## Configuration

Create a config file with your coinbase api key named the following

    ~/.btc/coinbase_api_key

The file should follow the format

    api_key=1234567890

### Available Commands

    btc           # Retrieve the current spot-rate price
    btc buy       # Retrieve the current buy price
    btc sell      # Retrieve the current sell price
    btc balance   # Retrieve current coinbase account balance

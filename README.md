# currency
A tool to convert currencies by utilizing crypto-currency exchanges.

# Draft
## Configuration

`$ cat /etc/currency/accounts.ini`
```
[DEFAULT]
type=Coinbase
auth_type=Oauth

[coinbase-usa]
currency=USD

[coinbase-fr]
currency=EUR
```

## Model
Exchange
  from_config()

# Crypto CLI

Crypto CLI is a __lightweight__ command line interface __written in one line__ to fetch the latest cryptocurrency prices and display them in the terminal.



## Usage

The top 10 cryptocurrencies are shown by default by entering
```
coin
```

For more coins, simply pass a number argument
```
coin 100
```

To get a specific price, simply use grep
```
coin 100 | grep VTC
```
<small>__note__ use "-i" flag on grep for case insensitive search<small>


## Development

```
git clone https://github.com/dillionverma/crypto-cli.git
cd crypto-cli
vim coin
```

## License


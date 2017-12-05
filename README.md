# Crypto CLI

Crypto CLI is a __lightweight__ command line interface __written in one line__ to fetch the latest cryptocurrency prices and display them in the terminal.

[![GitHub stars](https://img.shields.io/github/stars/dillionverma/crypto-cli.svg?style=social&label=Stars)](https://github.com/dillionverma/crypto-cli)
[![GitHub code size in bytes](https://img.shields.io/github/size/dillionverma/crypto-cli/coin.svg)](https://raw.githubusercontent.com/dillionverma/crypto-cli/master/coin)
[![license](https://img.shields.io/github/license/dillionverma/crypto-cli.svg)](https://github.com/dillionverma/crypto-cli)

![screenshot](https://github.com/dillionverma/crypto-cli/blob/master/screenshot.png)

## Installation
```
curl "https://raw.githubusercontent.com/dillionverma/crypto-cli/master/coin" -o /usr/local/bin/coin && chmod +x /usr/local/bin/coin
```

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

MIT License

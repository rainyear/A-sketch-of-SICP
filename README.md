# A Sketch of SICP (中文)

SICP in IPython Notebook with Scheme kernel.

<!-- BADGES/ -->
[![BitCoin donate button](https://img.shields.io/badge/Bitcoin-donate-2b71b1.svg?style=plastic)](https://www.coinbase.com/rainyear)
[![Tenpay donate button](https://img.shields.io/badge/Tenpay-donate-brightgreen.svg?style=plastic)](https://github.com/rainyear/lolita/wiki/Donation#tenpay)
[![Alipay donate button](https://img.shields.io/badge/Alipay-donate-orange.svg?style=plastic)](https://github.com/rainyear/lolita/wiki/Donation#alipay)
<!-- /BADGES -->

## Run this notebook locally

### Build python3 virtual env

```sh
## Create virtual env

python3 -m venv venv3

# if you're using zsh
source venv3/bin/activate

## Install ipython

pip install "ipython[notebook]"

# Might need to re-activate venv
deactivate && source venv3/bin/activate
```

### Install [Scheme kernel](https://github.com/Calysto/calysto_scheme)

```sh
# pip install calysto-scheme not work!
git clone https://github.com/Calysto/calysto_scheme.git
cd calysto_scheme

# under venv
python setup.py install
```

### Run notebook server

```sh
ipython notebook
```

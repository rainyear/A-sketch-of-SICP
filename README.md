# A Sketch of SICP (中文)
SICP in IPython Notebook with Scheme kernel.

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

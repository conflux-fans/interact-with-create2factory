# conflux create2 template

A template project presenting how to interact with [Create2Factory](https://github.com/Conflux-Chain/CIPs/blob/master/CIPs/cip-31.md) in Python.

## Setup

### install dependencies

```bash
pip install -r requirements.txt
```

### set secret key

```bash
export TESTNET_SECRET=0xblablabla
```

and replace `./template.json` with the contract metadata you want to deploy

### run 

```bash
python main.py
```

output example

```
salt 181655016474: CFXTEST:TYPE.CONTRACT:ACD....................
Ready to deploy? y/n
y
begin deployment...
successfully deployed at CFXTEST:TYPE.CONTRACT:ACD....................
```

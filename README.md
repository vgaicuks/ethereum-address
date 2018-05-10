# ethereum-address
Ethereum address validation with python

This is a clone of the [ethereum-address on js](https://github.com/cilphex/ethereum-address)
[`isAddress`](https://github.com/ethereum/web3.js/blob/master/lib/utils/utils.js)
utility method on python

## Install

```
pip install ethereum-address
```

## Usage

```python
from etherium_address import is_address

if is_address(value):
    print('Valid ethereum address.')
else:
    print('Invalid Ethereum address.')
```

## API

### is_address (address)

Returns true if the address (string) is an Ethereum address

### is_checksum_address (address)

Returns true if the address (string) is an Ethereum checksum address

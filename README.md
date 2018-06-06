# How to obtain your blockchain application ID

Confirm your application by interacting with our HR smart contract on the Ethereum Ropsten network:

1. Submit a hash (Keccak-256) of your email address using the `apply()` function.
2. Retrieve your application ID using the `getApplicationID()` function.
3. Copy your application ID and paste it in the application form.

:warning: :warning: Ropsten is a testnet network, **you do not need real Ether**.

### Additional information

Contract address: 
```
0xcbbfbafedb0eb83016d2a96a4e80d30b20fa3e30
```

Contract API: 
```
[{"constant": false,"inputs": [{"name": "hash","type": "bytes32"}],"name": "apply","outputs": [],"payable": false,"stateMutability": "nonpayable","type": "function"},{"constant": true,"inputs": [{"name": "email","type": "string"}],"name": "getApplicationID","outputs": [{"name": "","type": "uint256"}],"payable": false,"stateMutability": "view","type": "function"}]
```

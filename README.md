ERC20 Token for Crypto Global Capital - CredoEx

## what you need to change before deploy? 

You need to change the contract address before deploy the contract. change 0x91556f2CB7367b3047347a29C1FC854b26A580f4 to your contract address in line 6, 133, 134.

### line 6
```
// Deployed to : 0x91556f2CB7367b3047347a29C1FC854b26A580f4
```

### line 132
```
balances[0x91556f2CB7367b3047347a29C1FC854b26A580f4] = _totalSupply;
```

### line 133
```
emit Transfer(address(0), 0x91556f2CB7367b3047347a29C1FC854b26A580f4, _totalSupply);
```
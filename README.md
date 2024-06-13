# Metacrafters_ETH-Project
Token contract in solidity. This Solidity program is a simple tolen contract program that demonstrates the basic syntax and functionality of the Solidity programming language.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has two main functions "mint" and "burn" whose function is to add or delete the tokens from the balance.

### mint() function
```javascript
    function mint(address a, uint n) public {
        SupplyAmount += n;
        amount[a] += n;
    }
```
### burn() function
```javascript
    function burn( address a, uint n) public {
        if(amount[a]>= n){
            SupplyAmount -= n;
        amount[a] -= n;
        }
    }
```
## Authors

Mohit Sharma

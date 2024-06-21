# Metacrafters Ethereum Token Contract

A simple token contract demonstrating the basic syntax and functionality of the Solidity programming language.

## Description

This project features a basic token contract written in Solidity for the Ethereum blockchain. It includes two primary functions, `mint` and `burn`, which enable the addition and removal of tokens from user balances. This project serves as an introduction to smart contract development using Solidity.

## Getting Started

### Installing

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Metacrafters_ETH-Project.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd Metacrafters_ETH-Project
    ```
3. **Install dependencies** (if any, specify here).

### Executing program

1. **Compile the contract** using a Solidity compiler like `solc` or within an IDE like Remix.
2. **Deploy the contract** to an Ethereum testnet or local blockchain instance using a tool like Truffle or Remix.
3. **Interact with the contract**:
    - **Mint tokens**:
      ```solidity
      function mint(address a, uint n) public {
          SupplyAmount += n;
          amount[a] += n;
      }
      ```
    - **Burn tokens**:
      ```solidity
      function burn(address a, uint n) public {
          if(amount[a] >= n){
              SupplyAmount -= n;
              amount[a] -= n;
          }
      }
      ```

## Help

For common issues or troubleshooting steps, refer to the following:

1. **Compiler errors**: Ensure you are using a compatible Solidity version.
2. **Deployment issues**: Verify network configurations and account balances.

If you need further assistance, consult the Solidity documentation or community forums.

## Authors

Contributors names and contact info:

Mohit Sharma  
[@Linkdin](https://www.linkedin.com/in/mohit-sharma-4102bb298/)

Metacrafter Chris  
[@metacraftersio](https://twitter.com/metacraftersio)

## License

This project is licensed under the MIT License

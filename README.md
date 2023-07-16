# EthereumAssesment

# Introduction

This contract implements a simple token contract called "MyToken" with basic functionalities like minting and burning tokens. The token name is set to "BITCOIN" and the token abbreviation is set to "BTC". The total supply of tokens is initially set to 0.

## Usage

To use this contract, follow the steps below:

1. Deploy the contract on an Ethereum-compatible blockchain network of your choice.

2. Interact with the contract using a blockchain wallet or through a smart contract interface.

### Contract Variables

- `TokenName`: A public string variable that represents the name of the token.

- `TokenAb`: A public string variable that represents the abbreviation or symbol of the token.

- `totalSupply`: A public uint variable that holds the total supply of tokens.

### Mapping

- `balances`: A mapping variable that maps addresses to their corresponding token balances. It stores the balance of each address.

### Mint Function

The `mint` function allows the contract owner to create and distribute new tokens. It takes two parameters: `_address` (the recipient's address) and `_value` (the amount of tokens to be minted). The function increases the total supply and updates the balance of the recipient's address.

### Burn Function

The `burn` function allows token holders to burn or destroy their tokens. It takes two parameters: `_address` (the address of the token holder) and `_value` (the amount of tokens to be burned). The function checks if the token holder has a sufficient balance and then reduces the total supply and updates the balance of the token holder's address.

## Contributing

This code is provided as a basic example and does not currently accept contributions. However, you can fork the repository, make modifications, and use it as a starting point for your own token contract.

## Issues

If you encounter any issues or have suggestions for improvements, please open an issue on the repository's issue tracker.

## Author

 ADITYA SINGH

## License

This code is provided under the [MIT License](https://opensource.org/licenses/MIT).




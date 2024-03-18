#MyToken Contract

This Solidity contract is a basic implementation of a token contract named MyToken. It includes functionalities for minting new tokens and burning existing tokens.

##License

This contract is licensed under the MIT License. See the SPDX-License-Identifier in the contract file for more details.

##Prerequisites

    Solidity compiler version 0.8.18 or higher
    Ethereum development environment (e.g., Remix IDE, Truffle, etc.)

##Deployment

    Copy the contract code from MyToken.sol.
    Compile the contract using a Solidity compiler compatible with version 0.8.18. and above.
    Deploy the compiled contract to an Ethereum network of your choice.

##Contract Details

##Public Variables

    tokenName: The name of the token, set to "OXEN".
    tokenAbbrv: The abbreviation of the token, set to "OX".
    totalSupply: The total supply of tokens, initially set to 0.

##Mapping

    balances: A mapping that stores the balances of addresses holding the tokens.

##Mint Function

    mint(address _address, uint256 _value): A function to mint new tokens and assign them to the specified address. It increases the total supply and the balance of the address.

##Burn Function

    burn(address _address, uint256 _value): A function to burn (destroy) existing tokens from the specified address. It reduces the total supply and the balance of the address, but only if the address has sufficient tokens to burn.

##Usage

    Deploy the contract to an Ethereum network.
    Use the mint function to create new tokens and assign them to addresses.
    Use the burn function to destroy tokens from addresses.

##Contributing

Contributions to this contract are welcome. Fork the repository, make your changes, and submit a pull request.

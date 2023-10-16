# SimpleToken Contract

This Solidity smart contract implements the ERC20 standard for a basic token.

## License

This code is under the MIT License. See [LICENSE](LICENSE) for details.

## Prerequisites

- Solidity ^0.8.0

## Functions

### `transfer`

Transfers tokens from the sender's address to another address.

``solidity
function transfer(address _to, uint256 _value) public returns (bool success) {
    // ... (transfer function code)
}
`mint'
Mints new tokens and assigns them to an address.
function mint(address _to, uint256 _value) public returns (bool success) {
    // ... (mint function code)
}

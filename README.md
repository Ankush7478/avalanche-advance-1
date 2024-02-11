**README**

This repository contains two Solidity smart contracts: `Vault.sol` and `ERC20.sol`. Below is an overview of each contract along with usage instructions.

### Vault.sol

**Description:**
`Vault.sol` is a smart contract that acts as a vault for ERC20 tokens. It allows users to deposit and withdraw ERC20 tokens while maintaining a record of token balances and ownership shares within the vault.

**Features:**
- Deposit: Users can deposit ERC20 tokens into the vault, receiving ownership shares equivalent to the deposited amount.
- Withdraw: Users can withdraw their ownership shares from the vault, receiving back ERC20 tokens proportional to their shares.

**Usage:**
1. Deploy the `Vault.sol` contract, passing the address of the ERC20 token contract to the constructor.
2. Interact with the deployed `Vault` contract:
   - Call the `deposit` function to deposit ERC20 tokens into the vault.
   - Call the `withdraw` function to withdraw ERC20 tokens from the vault.

### ERC20.sol

**Description:**
`ERC20.sol` is an implementation of the ERC20 token standard. It provides basic functionalities for creating and managing ERC20 tokens, including transfer, approval, allowance, minting, and burning.

**Features:**
- Transfer: Allows users to transfer tokens to other addresses.
- Approve: Allows users to approve another address to spend tokens on their behalf.
- TransferFrom: Allows approved addresses to transfer tokens on behalf of the token owner.
- Mint: Allows the contract owner to create new tokens and assign them to an address.
- Burn: Allows token holders to destroy their own tokens.

**Usage:**
1. Deploy the `ERC20.sol` contract.
2. Interact with the deployed `ERC20` contract:
   - Transfer tokens using the `transfer` function.
   - Approve other addresses to spend tokens using the `approve` function.
   - Transfer tokens on behalf of other addresses using the `transferFrom` function.
   - Mint new tokens using the `mint` function (only accessible to the contract owner).
   - Burn existing tokens using the `burn` function.

## Author

swagath

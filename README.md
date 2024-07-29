# Swisstronik Mint 100 ERC-20 tokens

This project demonstrates deploying a Swisstronik contract and upgrading it using Hardhat and OpenZeppelin's upgrades plugin. It includes scripts to set and get messages from the deployed contract using Swisstronik's shielded transactions.

## Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later)

## Installation

1. Clone the repository:

```sh
git clone https://github.com/hassan0smp/SwissTronik-ERC20.git
cd SwissTronik-ERC20
```

2. Run the setup script:

```sh
chmod +x erc20.sh && ./erc20.sh
```


## Scripts

### `deploy.js`

This script deploys the ERC-20 contract and saves the deployed contract address to `contract.txt`.

### `mint.js`

This script mints 100 tokens using the deployed contract. It reads the contract address from `contract.txt`.

### `transfer.js`

This script transfers tokens from the contract to a specified address. It reads the contract address from `contract.txt`.

## Notes

- Ensure your private key is kept secure.
- The `transfer.js` script is set to transfer tokens to the address `0x16af037878a6cAce2Ea29d39A3757aC2F6F7aac1` with an amount of `1 * 10 ** 18` tokens. Modify these values as needed.
  
- Now visit : [Click Here](https://github.com/hassan0smp/SwissTronik-ERC20/blob/main/upload-to-github.md) to upload these codes in your github repository

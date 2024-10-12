# Token Swap - Quantity Fetch using PancakeSwap

This project fetches the quantity of tokens you will receive when swapping a specified amount of tokens on PancakeSwap. It connects to the Binance Smart Chain (BSC) using `ethers.js` to interact with smart contracts.

## Features

- Fetch the equivalent quantity of another token when swapping.
- Uses `ethers.js` to interact with PancakeSwap's router and factory smart contracts.
- Supports BSC mainnet connection for real-time data.

## Prerequisites

Make sure you have the following installed:

- Node.js v14 or higher
- npm (Node Package Manager)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/token-swap-quantity-fetch.git
2. **Navigate to the project directory:**
   ```bash
   cd token-swap-quantity-fetch
3. **Install dependencies:**
   ```bash
   npm install ethers


## Usage

1. **Set up your PriceFetch.js script:**
   The script contains the following main components:

   Address List: Configure the contract addresses of the tokens you want to swap.
   ABI Information: Define the ABI for each contract you're interacting with.

2. **Run the script:**
   ```bash
   node PriceFetch.js


## Code Overview

**PriceFetch.js:** Main file that sets up connection to BSC, interacts with PancakeSwap router, and fetches token amounts.
**AddressList.js:** Contains the addresses of the tokens you're fetching data for.
**AbiInfo.js:** Contains the ABI definitions for the contracts.

## License
This project is open-source and available under the MIT License.

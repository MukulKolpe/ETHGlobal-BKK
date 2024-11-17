# ETHGlobal Bangkok - CrossChainPort 🚀

A decentralized cross-chain liquidity platform powered by Chainlink CCIP and Polygon AggLayer. Say goodbye to burns, wraps, and intermediaries—swap assets seamlessly across chains with unmatched security and simplicity!

## Tech Stack 🧰

- Solidity
- ethers.js
- Next.js
- React.js
- Foundry
- OpenZeppelin
- ConnectKit
- TypeScript
- JavaScript
- TailwindCSS
- Alchemy
- Wagmi
- Chainlink CCIP
- Blockscout
- Polygon Agglayer
- Pyth
- Worldcoin

## Foundry Setup 🚧

### Prerequisites

Before you begin, ensure you have the following installed:

- Follow the installation instructions in the [Foundry documentation](https://book.getfoundry.sh/).

For Windows users, it is recommended to use Windows Subsystem for Linux (WSL) for the Foundry setup.

### Getting Started

#### Cloning the Repository

1. Clone the HackOnBlocks repository:

```bash
git clone https://github.com/MukulKolpe/ETHGlobal-BKK
```

2. Navigate to the `contracts/` directory:

```bash
cd ETHGlobal-BKK/contracts/
```

#### Setting Up Environment Variables

1. Create a file named `.env` in the contracts directory.

2. Configure the `.env` file according to the provided `.env.example` file.

#### Installing Dependencies

Install the necessary dependencies for the Foundry setup:

```bash
forge install
```

#### Building the Project

Build the project with the following command:

```bash
forge build
```

## Frontend Setup 🚧

**Note:** Update the compiled ABIs of the contracts in the `/frontend/src/utils/abis/` directory.

1. From the root, navigate to the `frontend/` directory:

```bash
cd ETHGlobal-BKK/frontend/
```

2. Create a `.env` file in the root directory of the project:

```bash
touch .env
```

3. Refer to `.env.example` to update the `.env` file.

4. Install Dependencies:

```bash
yarn
```

5. Run the project at `localhost:3000`:

```bash
yarn run dev
```

## CONTRACT ADDRESSES

### BASE SEPOLIA

PoolFactory.sol - [0x275fC6E5b9BCE1b756EacA955b7758070099e07d](https://base-sepolia.blockscout.com/address/0x275fC6E5b9BCE1b756EacA955b7758070099e07d
)

### OPTIMISM SEPOLIA

PoolFactory.sol - [0xfa24eaD3De76045f875998dd1d75562057cEB26d](https://optimism-sepolia.blockscout.com/address/0xfa24eaD3De76045f875998dd1d75562057cEB26d)

### ETHEREUM SEPOLIA

PoolFactory.sol - [0x86552b6aaf1D7f0ffFc7cEe029A501e4883308bC](https://eth-sepolia.blockscout.com/address/0x86552b6aaf1D7f0ffFc7cEe029A501e4883308bC)

### ARBITRUM SEPOLIA

PoolFactory.sol - [0x7E33E711612Af4c4522d89C8F88f7eA9E925a5D3
](https://sepolia-explorer.arbitrum.io/address/0x7E33E711612Af4c4522d89C8F88f7eA9E925a5D3
)

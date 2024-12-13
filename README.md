# Blockchain Explorer

## Table of Contents

- [Project Description](#project-description)
- [Live Demo](#live-demo)
- [Repository](#repository)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Project Description

Blockchain Explorer is a web application that allows users to query block and transaction data directly from the Ethereum blockchain. It features integration with MetaMask for seamless blockchain interaction or backend APIs when MetaMask is not connected. The app enables users to search for block data by block hash or block number and fetch transaction details by transaction hash.

## Live Demo

Access the application here:
[https://timely-muffin-62994c.netlify.app](https://timely-muffin-62994c.netlify.app)

## Features

- **Block Data Query**: Fetch Ethereum block data using block hash or block number.
- **Transaction Data Query**: Retrieve transaction details using transaction hash.
- **MetaMask Integration**: Connect MetaMask wallet to fetch data from the blockchain directly via MetaMask provider.
- **Backend API Support**: Fetch blockchain data via backend APIs when MetaMask is not connected.
- **Responsive UI**: User-friendly interface to search and view blockchain data.

## Technologies Used

- **Frontend**:
  - Next.js (for UI development and backend functionality)
  - Tailwind CSS (for styling)

- **Backend**:
  - Next.js API routes
  - Web3.js or ethers.js (to interact with the Ethereum blockchain)

- **Blockchain Interaction**:
  - MetaMask (for wallet integration)
  - Ethereum JSON-RPC

- **Additional Tools**:
  - Docker (for containerization)

- **Deployment**:
  - Netlify (Full-stack hosting)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Tanaychoubey/blockchain-explorer-web3js.git
   cd blockchain-explorer-web3js
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables (see below).
4. Run the application:
   ```bash
   npm run dev
   ```

## Environment Variables

### Backend and Frontend (.env.local)

```env
NEXT_PUBLIC_ETH_NODE_URL=your-ethereum-node-url
NEXT_PUBLIC_METAMASK_PROVIDER_URL=your-metamask-provider-url
```

## Usage

1. Open the app in your browser at `http://localhost:3000`.
2. Use the search interface to query blockchain data by:
   - **Block Hash or Number**: View block details.
   - **Transaction Hash**: View transaction details.
3. Connect your MetaMask wallet to fetch data directly from the blockchain.
4. If MetaMask is not connected, data will be fetched from the backend APIs.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

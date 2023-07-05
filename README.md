Blockchain Explorer application that uses Ethereum blockchain and
Web3.js or Ether.js library. It allows users to Query block and transaction data using
block hash, block number, or transaction hash. Metamask wallet is integrated for
seamless interaction with decentralized applications. The application uses Geth node
for backend data fetching when Metamask is not connected

## Getting Started

Install go ethereum(geth) in your system.

Run the geth

Add geth running port URL in const in web3 

web3 = new Web3(
      "https://121.0.0.1:8545"
    ); // Replace with the URL of your geth node
    
Run the development server:

```bash
npm run dev
# or
yarn dev
```

## Deployed on netlify

https://timely-muffin-62994c.netlify.app

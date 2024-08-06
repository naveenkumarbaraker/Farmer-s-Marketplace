
<h1 align="center">Blockchain-Based Farmers Marketplace<br /></h1>  

## 🌾 Blockchain-Based Farmers Marketplace Project Built with Ethereum + React.js + Metamask + Truffle 🚜

## Technologies Used:
 - Ethereum: Blockchain platform for deploying smart contracts.
 - React.js: Frontend library for building user interfaces.
 - Ganache: Personal blockchain for Ethereum development that you can use to deploy contracts, develop your applications, and run tests.
 - Truffle: Development environment, testing framework, and asset pipeline for Ethereum.
 - MetaMask: Crypto wallet and gateway to blockchain apps that interacts with the Ethereum blockchain.
 - Pinata: IPFS pinning service used to store and manage files on the InterPlanetary File System (IPFS).

   
### Prerequisites
- Node.js 🌐
- Truffle 🖥️
- Ganache 🛠️
- Metamask 🔑

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/blockchain-farmers-marketplace.git
   cd blockchain-farmers-marketplace
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start Ganache:**
   ```sh
   ganache-cli
   ```

4. **Compile and deploy smart contracts:**
   ```sh
   truffle migrate
   ```

5. **Run the server:**
   ```sh
   cd server
   ```

6. **Start the frontend:**
   ```sh
   cd client
   npm start
   ```

## Usage

### Metamask Configuration:
1. Install MetaMask extension in your browser. 🦊
2. Connect MetaMask to the local Ganache network. 🌐

### Pinata Configuration
**Further used Pin assets using Pinata:**
- Sign up for a Pinata account at Pinata. 📝
- Use Pinata’s API or web interface to upload and manage files on IPFS. 🌌

### Accessing the Marketplace:
1. Open http://localhost:3000 in your browser. 🌐
2. Register as a farmer or consumer. 🧑‍🌾🛒
3. Farmers can add products, and consumers can browse and purchase products. 🛒


## Smart Contracts
### Overview
- `ProductRegistry.sol`: Manages the registry of products. 📦
- `Marketplace.sol`: Handles buying and selling transactions. 💰
- `UserRegistry.sol`: Manages user registrations. 🧑‍💻

### Deployment
Smart contracts are deployed using Truffle. The deployment scripts are located in the `migrations` folder.

### Testing
Smart contracts are tested using Truffle. To run tests, use:
```sh
truffle test
```

## API Endpoints

### Authentication
- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Login a user.

### Products
- `GET /api/products`: Get all products.
- `POST /api/products`: Add a new product.

### Orders
- `GET /api/orders`: Get all orders.
- `POST /api/orders`: Place a new order.

## Results
The platform has been tested to ensure the integrity and security of transactions. Key snapshots include:
- Home Page: Overview of the marketplace. 🏠
- Add Product: Interface for farmers to add products. ➕📦
- Admin Page: Administration interface for managing the platform. ⚙️
- Product Listing: Display of available products. 🛒
- Order Confirmation: Order processing confirmation screen. ✅

## Conclusion
This project aims to empower farmers, enhance supply chain efficiency, and offer consumers fresh produce with verified provenance. By integrating blockchain technology with e-commerce, it envisions a more equitable and transparent agricultural marketplace. 🌱💫

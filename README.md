<p align="center">
  <img align="center" src="https://github.com/AkhileshThite/polytickets-landingpage/blob/main/src/images/logo.png" width="200" height="200"></img>
</p>

<h1 align="center">PolyTickets</h1>

<p aign="center">
  <p align="center">Landing page website: <a href="https://polytickets.on.fleek.co"></a>https://polytickets.on.fleek.co</p>
  <p align="center">Marketplace dapp: <a href="https://polytickets-marketplace.vercel.app/"></a>https://polytickets-marketplace.vercel.app/</p>
</p>

<div align="center">
  <img src="https://img.shields.io/github/repo-size/akhileshthite/polytickets-marketplace" alt="repo size">
  <img src="https://img.shields.io/badge/Platform-Polygon-purple.svg" alt="platform">
</div>

## Run locally
1. Clone the project locally, change into the directory:
```bash
git clone https://github.com/AkhileshThite/polytickets-marketplace

cd polytickets-marketplace
```

2. install dependencies
```bash
npm install

# or

yarn
```

3. Start the application.
```bash
npm run dev
```

## Development setup
1. Clone the project locally, change into the directory, and install the dependencies:
```bash
git clone https://github.com/AkhileshThite/polytickets-marketplace

cd polytickets-marketplace

# install dependencies using `npm` or `yarn`.

npm install

# or

yarn
```

Create `.secret` and `.env` files, 
* Put private key of your wallet account in `.secret`.
* Put `NEXT_PUBLIC_WORKSPACE_URL=https://rpctest.meter.io/` in `.env` file.

2. Start the local Hardhat node.
```bash
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window.

```bash
npx hardhat run scripts/deploy.js --network meter
```

4. Start the application.
```bash
npm run dev
```

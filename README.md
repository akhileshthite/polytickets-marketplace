<p align="center">
  <img align="center" src="https://github.com/AkhileshThite/polytickets-landingpage/blob/main/src/images/logo.png" width="250" height="250"></img>
</p>

<h1 align="center">PolyTickets</h1>

<p aign="center">
  <p align="center">Decentralized video sharing & social media platform on Ethereum blockchain.</p>
  <p align="center">Website: <a href="https://polytickets.on.fleek.co"></a>https://polytickets.on.fleek.co</p>
</p>

<div align="center">
  <!--<img src="https://img.shields.io/github/v/release/AkhileshThite/DTube?color=1FC71F" alt="GitHub release" />-->
  <img src="https://img.shields.io/github/repo-size/akhileshthite/polytickets-marketplace" alt="repo size">
  <img src="https://img.shields.io/badge/Platform-Polygon-purple.svg" alt="platform">
</div>

## Local setup
To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:
```
git clone https://github.com/AkhileshThite/polytickets-marketplace

cd polygon-ethereum-nextjs-marketplace

# install using NPM or Yarn
npm install

# or

yarn
```
2. Start the local Hardhat node
```
npx hardhat node
```
3. With the network running, deploy the contracts to the local network in a separate terminal window

```
npx hardhat run scripts/deploy.js --network localhost
```
4. Start the app
```
npm run dev
```
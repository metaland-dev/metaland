**Pikaster** is a card battle game featuring Pikaster (NFT) with the goal to create a “Truly-play& Truly-Earn” Game through innovative product features to bring players both extraordinary gaming experience and handsome economic returns. Pikaster is strategically invested by KuCoin and will launch IGO on it as the first project on April 11 and IDO on MojitoSwap on April 25.

Here are the Game Features of Piakster:

1. In-game wallet and marketplace in the App

2. Creative Three-Token Economic Model 

3. Profit-Sharing System 

4. More ways of gameplay

---

### The project include customed ERC20 and ERC721 Template.
```
.
├── README.md
├── contracts
│   ├── ERC20Template.sol
│   └── ERC721Template.sol
├── hardhat.config.js
├── package-lock.json
├── package.json
└── scripts
    ├── deploy.js
    └── helpers.js
```

### Prerequisite

#### Node.js 

Hardhat recommend using the current LTS Node.js version. You can learn about it [here](https://nodejs.org/en/about/releases/) 

recommend v16.x, you can download [here](https://nodejs.org/download/release/latest-v16.x/)

#### .env file

Prepare `.env` file under project root directory.

```.env
ALCHEMY_KEY = "YOUR_ALCHEMY_KEY"
ACCOUNT_PRIVATE_KEY = "YOUR_PRIVATE_KEY"
NETWORK="rinkeby"
```

### Compile
```SHELL
npm ci
```

```SHELL
npx hardhat compile
```

### Deploy

```
npx hardhat deployERC20
npx hardhat deployERC721
```

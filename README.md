WinGoal is the first Web3.0 Decentralized App bringing FIFA World Cup from Web2.0 to Web3.0.

WinGoal = World Cup Soccer Gaming & Real-Time Predictions + Reality Sports + Live Match Streaming.

WinGoal is Free-To-Play with no barriers to entry. Players will earn soccer-themed tokens as rewards.

Participate in Burn-To-Earn, via Sports , and in Win-To-Earn-More, via Competitive Gaming and World Cup Predictions in real-time!

WinGoal is built on Polygon and powered by the Unity Engine and Opta.

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

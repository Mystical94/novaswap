# NovaSwap
A decentralized exchange on EVMOS Chain based on UniswapV2 AMM mechanism

### Swap Page
<img src="UserInterface/src/assets/novaswap_images/swap_page.png" alt="Logo">

### Pool Page
<img src="UserInterface/src/assets/novaswap_images/pool_page_dark.png" alt="Logo">

## Deploying the NovaSwap on local machine

### Clone the repository

After cloning the repository move into the UserInterface Directory

```sh
cd UserInterface
```

install dependencies using **yarn** or **npm**

- **having some dependency version problems in yarn, so advised to use npm commands instead**

```sh
yarn

or

npm install
```
If using Windows then run these two commmands after npm install

```sh
rm -r ./node_modules/@uniswap/sdk

And then this command

cp -r ./forks/@uniswap/sdk ./node_modules/@uniswap/sdk
```

start the development server
```sh
yarn start

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```
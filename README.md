# gkd-rescuer

This is a React/Vite app containing:

- Tailwind and Shadcn UI for styling
- [Gill](https://gill.site/) Solana SDK
- Shadcn [Wallet UI](https://registry.wallet-ui.dev) components

## Getting Started

### Installation

#### Download the template

```shell
npx create-solana-dapp@latest -t gh:solana-foundation/templates/gill/gkd-rescuer
```

#### Install Dependencies

```shell
npm install
```

### Start the app

```shell
npm run dev
```

### For local testing

change the wallet public key inside `./runbooks/gkd-rescuer.tx`

```shell
surfpool start
surfpool run ./runbooks/gkd-rescuer.tx <== run this to setup wallet with $KID tokens
```

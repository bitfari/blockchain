# Bitfari Blockchain Explorer / Stacks 2.0 Explorer for Bitfari


### Getting started

The Bitfari Blockchain Explorer is built with react, [next.js](https://github.com/zeit/next.js) and [@stacks/ui](https://github.com/blockstack/ui). To run the explorer locally, you can clone this repo and install the dependencies needed. Make sure you have `yarn` installed.

```sh
yarn
```

### Env variables

The application needs a couple of env variables to work properly:

```
NEXT_PUBLIC_MAINNET_API_SERVE=https://stacks-node-api.stacks.co
NEXT_PUBLIC_TESTNET_API_SERVER=https://stacks-node-api.testnet.stacks.co
NEXT_PUBLIC_LEGACY_EXPLORER_API_SERVER=https://explorer-api.legacy.blockstack.org
NEXT_PUBLIC_DEPLOYMENT_URL=https://explorer.stacks.co
NEXT_PUBLIC_MAINNET_ENABLED="true"
NEXT_PUBLIC_DEFAULT_POLLING_INTERVAL="10000"
```

### Run in development mode

To build and run the application, you can run this yarn task which will launch the application at http://localhost:3000.

```sh
yarn dev
```

### Building for production

To build for production, run `yarn build` which will run the default next.js build task.

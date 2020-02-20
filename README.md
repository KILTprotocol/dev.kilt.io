# About KILT

**[KILT][website] is an open-source blockchain protocol for issuing self-sovereign verifiable, revocable, anonymous credentials and enabling trust market business models in the Web 3.0.**

## Explore

### <img width="40" src="./imgs/chain.jpg"> KILT Blockchain

See the currently running nodes on our [telemetry][telemetry]. Dive into the transactions happening on the KILT Blockchain at this very moment on our [blockchain explorer][chain-explorer].

### <img width="34" src="./imgs/faucet.jpg"> Faucet

Request test money from the [Mash-Net Faucet][faucet].

### <img width="40" src="./imgs/demo.jpg"> Demo-client

Check out our the [demo-client][demo], a sample application that showcases all features of the KILT Protocol and connects to the KILT Blockchain.

## Learn

### <img width="30" src="./imgs/workshop.jpg"> Tutorial/Workshop

Hands-on: try out the [101 Tutorial/Workshop][workshop] to quickly ramp-up on KILT's core concepts and SDK.

### <img width="30" src="./imgs/whitepaper.jpg"> Whitepaper

Dive deeper into KILT concepts by taking a look at the [whitepaper][whitepaper].

## Build!

Writing apps for blockchain is not just for blockchain developers anymore.

### <img width="30" src="./imgs/tools.jpg"> SDK

Use the [KILT SDK][sdk-js-repo] to easily build JavaScript- or TypeScript-based applications for credentials.

### <img width="28" src="./imgs/phone_hand.jpg"> Mobile wallet

**Build a demo in no time.**
Use our [demo-mobile-wallet][demo-mobile-wallet-repo] and easily customize the claim/credential type, branding and colors, to demo your own KILT-based use case.


# Software Overview

## Codebases and Dependencies

<p align="center">
<img width="820" src="./imgs/overview.jpg">  
  <div align="center"><sub><sup>Codebases and Dependencies</sup></sub></div> 
</p>

```
🐥 = DEV environment
🐓 = PROD environment, stable
```

## Infrastructure / CI

<p align="center">
<img width="620" src="./imgs/infrastructure.jpg">  
  <div align="center"><sub><sup>Infrastructure</sup></sub></div> 
</p>

## Source code and deployed instances

|                             | WHERE THE CODE IS (OPEN-SOURCE)               | WHERE IT IS DEPLOYED (AWS): DEV ENVIRONMENT🐥 | WHERE IT IS DEPLOYED (AWS): PROD ENVIRONMENT🐓 |
| --------------------------- | --------------------------------------------- | :-------------------------------------------: | :--------------------------------------------: |
| BLOCKCHAIN                  | [mashnet-node][mashnet-node-repo]             |           full-nodes.devnet.kilt.io           |               full-nodes.kilt.io               |
| SDK                         | [sdk-js][sdk-js-repo]                         |                     (not)                     |                     (not)                      |
| DEMO APP                    | [demo-client][demo-client-repo]               |          [demo.devnet][demo.devnet]           |                  [demo][demo]                  |
| DEMO APP                    | [demo-mobile-wallet][demo-mobile-wallet-repo] |                     (not)                     |                     (not)                      |
| DEMO APP COMPANION          | [prototype-services][prototype-services-repo] |            services.devnet.kilt.io            |                services.kilt.io                |
| DEMO APP COMPANION          | [faucet][faucet-repo]                         |        [faucet-devnet][faucet-devnet]         |                [faucet][faucet]                |
| BLOCKCHAIN OBSERVATION TOOL | [telemetry][telemetry-repo]                   |                     (not)                     |             [telemetry][telemetry]             |
| BLOCKCHAIN OBSERVATION TOOL | [polkadot-apps][polkadot-apps-repo]           |                     (not)                     |        [chain-explorer][chain-explorer]        |

# Community

Join our [Community Chat][cmy-channel]!


[cmy-channel]: https://riot.im/app/#/room/#kilt-general:matrix.org
[website]: https://kilt.io
[mashnet-node-repo]: https://github.com/KILTprotocol/mashnet-node
[sdk-js-repo]: https://github.com/KILTprotocol/sdk-js
[demo-client-repo]: https://github.com/KILTprotocol/demo-client
[demo-mobile-wallet-repo]: https://github.com/KILTprotocol/demo-mobile-wallet
[prototype-services-repo]: https://github.com/KILTprotocol/prototype-services
[faucet-repo]: https://github.com/KILTprotocol/faucet
[telemetry-repo]: https://github.com/KILTprotocol/substrate-telemetry
[polkadot-apps-repo]: https://github.com/KILTprotocol/polkadot-apps
[demo.devnet]: https://demo.devnet.kilt.io
[demo]: https://demo.kilt.io
[faucet-devnet]: https://faucet-devnet.kilt.io
[faucet]: https://faucet.kilt.io
[telemetry]: http://telemetry.kilt.io/#/KILT%20Testnet
[chain-explorer]: https://chain-explorer.kilt.io
[workshop]: https://kiltprotocol.github.io/kilt-workshop-101
[whitepaper]: https://kilt.io/wp-content/uploads/2020/01/KILT-White-Paper-v2020-Jan-15.pdf
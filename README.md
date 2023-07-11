ZetaChain
ZetaChain is a public, decentralized blockchain and smart contract platform built for omnichain interoperability.

What's in this repo?
Utilities to interact with ZetaChain's contracts from your dApp, scripts, or tests.
Interfaces to easily develop omnichain contracts.
Omnichain dApp example contracts.
Protocol native contracts (Zeta Token, Zeta Connector).
Learn more about ZetaChain
Check our website.
Read our docs.
Usage
Install Node.js LTS (previous versions may, but are not guaranteed to work).

Install yarn (make sure NPM has the right permissions to add global packages):

 npm i -g yarn
Install the dependencies:

 yarn
From the root folder, compile the contracts:

 yarn compile
Packages
Addresses
Example contracts
Protocol contracts
ZEVM contracts
Cross-repo commands
Package-specific commands
They run independently, only on the packages that implement them:

yarn compile
yarn clean
yarn test
Repo commands
They run once, across the whole repo:

yarn lint
yarn lint:fix
Contributing
We welcome (and appreciate) everyone's contributions. If you wanna contribute, read CONTRIBUTING.md for next steps.

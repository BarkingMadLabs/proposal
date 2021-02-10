## Barking mad

### Objectives
1. Easily create and trade NFTs

2. Focus on gamers - Marketplace, tools - wallet and creator

3. Focus on game developers - SDKs

4. Fast and cheap transactions.  Huge scale needed.

5. Community support


### Technology

Looking at the Polkadot ecosystem which offers a few options.

Two approaches to this.  One would be to implement the NFT layer in Smart contracts running on one of the parachains available.  At the moment of writing this would include Moonbeam and Edgeware.  Moonbeam offers an Ethereum Virtual Machine(EVM) pallet among others which allows a solution to be built in an EVM compatible language such as Solidity.  This brings the advantage of the toolset for Ethereum(Truffle, OpenZeppin etc) and the option to run on other chains, including Ethereum, when it has scaling, Edgeware and I think Tron.  It would also mean that NFTs already on chains like Ethereum could be interchanged using bridges such as ChainBridge (https://docs.moonbeam.network/integrations/bridges/ethereum/chainbridge/) which could help onboarding of existing users.  Edgeware also offers a smart contract pallet which provides support to write contracts in Ink! (https://substrate.dev/docs/en/knowledgebase/smart-contracts/)


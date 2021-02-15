## Project title needed here

### Objectives
1. Easily create and trade NFTs

2. Focus on gamers - Marketplace, tools - wallet and creator

3. Focus on game developers - SDKs

4. Fast and cheap transactions.  Huge scale needed.

5. Community support


### Technology

Looking at the Polkadot ecosystem which offers a few options.

Two approaches to this.  One would be to implement the NFT layer in Smart contracts running on one of the parachains available.  At the moment of writing this would include Moonbeam and Edgeware.  Moonbeam offers an Ethereum Virtual Machine(EVM) pallet among others which allows a solution to be built in an EVM compatible language such as Solidity.  This brings the advantage of the toolset for Ethereum(Truffle, OpenZeppin etc) and the option to run on other chains, including Ethereum, when it has scaling, Edgeware and I think Tron.  It would also mean that NFTs already on chains like Ethereum could be interchanged using bridges such as ChainBridge (https://docs.moonbeam.network/integrations/bridges/ethereum/chainbridge/) which could help onboarding of existing users.  Edgeware also offers a smart contract pallet which provides support to write contracts in Ink! (https://substrate.dev/docs/en/knowledgebase/smart-contracts/).  This may bring advantages but further investigation is needed to determine, if any, what they would be.  

The second approach would be a chain itself built on Substrate which could run as it's own Blockchain or as a Parachain if we were looking for the added security and interopability across other Parachains in the ecosystem.  This option does offer complete flexibility bringing many things to the table such as governance, staking, control on costs and a native token, customisation of the node(rpc for example), amongst other things.  This does however mean we would need to manage validators, community and governance.  This would mean extra management not only in terms of managing a blockchain community but managing this codebase which would need a higher level of expertise.  If we would want to be a Parachain we would need to lock a slot on the relay chain of Kusama, on prelaunch, and then Polkadot.  This means locking a large amount of funds (TODO - what is the cost in KSM/DOT) Crowdfunding and loans discussed in the following link. (https://polkadot.network/obtaining-a-parachain-slot-on-polkadot/).  Some reasoning and discussion around why you would choose one or the other. (https://wiki.polkadot.network/docs/en/build-build-with-polkadot#what-is-the-difference-between-building-a-parachain-a-parathread-or-a-smart-contract)

If we can overcome and organise how we would create the numbers of nodes needed to secure the network the best performing approach would be creating a chain directly as we would be able to guarentee higher transaction speeds and with time these would increase further.  Being a general purpose contract chain would see limitations but this doesn't remove the possibility that an initial version is built in Smart contracts and then moved to its own chain.  This does potentially have the drawback of how we move the assets stored on this initial chain to the new one.  Potentially starting with a chain may be better idea mid to long term.  

With its own parachain we would be able to support staking and governance giving token holders a means to vote on changes etc and allow this to be funded via a treasury.  It will also mean that the network would be supported by staking where stakers would earn tokens.  Items would be traded in the native token and a percentage of each transaction would be paid to treasury and maybe stakers.  Would need to think more on the economics here and token distribution on genesis.





---
sidebar_label: 'General FAQ'
sidebar_position: 0
---
# General

## What is Neo？

Neo is a distributed network which utilizes blockchain technology and digital identity to digitize assets and automate the management of digital assets using smart contracts. Neo network has two tokens, NEO representing the right to manage Neo blockchain and GAS representing the right to use the Neo Blockchain. 

## What developer communities does Neo have?

Neo has a large number of community groups worldwide that have been driving the development of the Neo ecosystem forward. These groups include:

- **COZ**, Global. Major projects include Neon Wallet, Dora, and the Neo Python Suite: https://github.com/CityOfZion
- **NeoResearch**, Brazil. Major projects include dBFT applied research and NeoCompiler Eco：https://github.com/NeoResearch
- **NeoSPCC**, Russia. Major projects include NeoFS and NeoGo：https://www.nspcc.ru/en
- **NGD Enterprise**, USA. Major projects include the Neo Blockchain Toolkit: https://ngdenterprise.com
- **NEXT**, China. Major projects include NeoLine and NeoTube：https://neonext.io
- **AxLabs**, Switzerland. Major projects include neow3j and NeoPlayground：https://github.com/neow3j
- **Red4Sec**, Spain. Neo blockchain and contract security audits：https://red4sec.com
- **NeoTracker**, USA. Major projects include NEO-ONE and NeoTracker: https://neo-one.io
- **Neo News Today**, USA. Major projects include NeoNewsToday.com and nDapp: https://neonewstoday.com

## What is GAS？How do I acquire GAS？

GAS is a native asset that represents the right to use the Neo Blockchain. The Neo network charges GAS to deploy assets, interact with smart contracts, and all transactions that modify the blockchain status. GAS is distribued to all wallets holding NEO in each block. The amount of GAS recieved can be increased by participating in Neo's governance and voting for a council candidate. On Neo N3, accruded GAS is claimed automatically by a wallet whenever there is a change in the NEO balance.

Unlike the Neo Legacy, there is no supply limit for Neo N3 GAS and system fees for transactions are burned.

## What consensus algorithms does Neo use？

Neo utilizes a delegated Byzantine Fault Tolerance (dBFT) algorithm which provides a  𝑓 = ⌊ (𝑛−1) / 3 ⌋  fault tolerance to a consensus system that comprises n nodes. 

There are several types of nodes in this mechanism, such as the ordinary nodes, the candidate nodes, the committee nodes, and the consensus nodes.  Anyone can start a transaction to become the candidate or vote for the candidate. Candidates with a certain amount votes are elected as committee members or consensus nodes. When a consensus needs to be passed, a speaker is randomly selected to decide the proposal, and then other consensus nodes vote according to the dBFT algorithm. If more than 2/3 of nodes agree to the proposal, the consensus is reached; otherwise, the speaker is re-elected and the voting process is repeated.  

## How to become a Neo consensus node？Is there any incentives？

Neo consensus nodes are elected by NEO holders. For more information see https://docs.neo.org/docs/zh-cn/basic/consensus/vote_validator.html. The network fee will be distributed to the consensus node who starts a new-block proposal of the block where corresponding transaction is included. The consensus node that packages transactions and proposes a new block will be rewarded the network fee of all transactions included in the block.

## What browsers are available for Neo blockchain?

<https://neo3.neotube.io/> is commonly used, or you can access http://ndapp.org/ and find all the browsers listed under the Explorer tab.

## How can I check the status of my transaction?

You can check it on any Neo blockchain explorer, such as https://neotube.io/.

## Is there an equivalent of ERC-20 standard for Neo?

Yes. NEP-17, the replacement of the standard NEP-5, is the Neo N3 token standard which outlines the specifications to be followed by contracts deployed on the Neo blockchain. 

## How to view NEP-17 assets in Neo-CLI？

To view NEP-17 assets invoke the  RPC API [getnep17balances](../n3/reference/rpc/latest-version/api/getnep17balances) or use the Neo-CLI command [balanceof](../n3/node/cli/cli#balanceof) .

## What is NEP-6？

NEP-6 is a wallet standard that specifies the wallet format, the definition of parameters in it, the creation rules of wallet address and so on. NEP-6 is applicable to several current Neo client versions including 2.7.6. The Neo client supports wallets in two formats,  sqlite wallet (in .db3) and NEP-6 wallet (in .json). Considering the processing speed, the sqlite wallet is strongly recommended for exchanges. 

## Can you store NEO the same way as Bitcoin? I am nervous about the storage safety.

Yes. If you are holding NEO, then you are always keeping it online. Storing private keys offline means your coins are safe and can not be touched.

## Is there a transfer fee between Neo wallets?

Yes. On Neo N3 any transfer transaction requires a certain amount of GAS.

## If I keep my NEO on an exchange, can I still get my GAS?

This depends on the exchange; some (like [Binance](https://www.binance.com/)) have chosen to give users their GAS when you leave your NEO on the exchange, while others (like [Bittrex](https://www.bittrex.com/)) keep the GAS for themselves. If you want to make sure you receive your Gas, move your NEO to a private wallet and manually claim your GAS.

## I have transferred my NEO balance from the exchange and the exchange kept 0.9750 NEO. However, I cannot send this anywhere because you need at least 1 NEO to be able to send. Can this amount be topped up, held or sold?

You can keep it there to be sold later, or you can buy additional NEO on the exchange so that your amount is more than 1 NEO. You can also exchange NEO to other tokens like USDT, GAS, etc.


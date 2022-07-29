# USDAO Stablecoin 

## Abstract

The motivation to develop a stablecoin like USDAO is to build an enterprise-friendly, easily
integrable and interoperable stablecoin that should not only be reliable as fiat currencies but
also open new doors of possibilities for businesses using blockchain technology. There is no
stablecoin protocol that have addressed the above-mentioned problems despite the market
being flooded with hundreds of stablecoin projects. We intend to provide a solution to this
issue.
We, at RUIT Foundation, have built The USDAO Stablecoin that would simplify transactions in
business processes and extend limits for cross-border global transactions by offering faster and
safer transactions, high liquidity, decentralized governance, multi blockchain compatibility and
many more advantages than our centralized and decentralized competitors.
We promise to deliver simpler implementation and easy integration of our technology into
your existing business. USDAO stablecoin is powered by multiple blockchains including
Ethereum which itself is a reputed and established market leader in decentralized application’s
technology.

## Role of the RUIT Foundation

The RUIT foundation is a not-for-profit corporation charged with the responsibility primarily to
focus on maintaining the USDAO ecosystem and nurturing the community. However, if a
situation occurs that requires immediate action to prevent any catastrophic event the
foundation holds the right to step in and take the right action. It is important to clarify, that the
foundation would never participate or promote any action that could cause an individual or a
party including the RUIT foundation itself any monetary benefit.
Having said that, these are few situations were the RUIT foundation holds the right to take
actions upon the following:
1. Upgrading or launching a new or improved version of USDAO
2. Adding new oracles or removing obsolete oracles
3. To ensure the safety of the pool and safeguard the interests of the users during
an unknown event
4. Raise funding by minting new ASSET tokens through governance at a chosen
market price.
5. Taking proactive measures required to safeguard and promote USDAO
ecosystem.

<i>“We believe in the principle of deploy and forget and we wish a situation mentioned above will never occur
where we would need to step in to safeguard our system. In the majority of the scenarios, the community shall
govern the USDAO Ecosystem through the governance protocol.”</i>
<p align="right">- USDAO Team</p>

## Problem Statement

In recent years cryptocurrencies have unlocked new horizons of digital transformations that
once seemed like an alien technology and mostly beyond comprehension. In the past decade,
we have seen Bitcoin, a true peer-to-peer decentralized digital asset that runs without any
government or central institution. Then came Ethereum that offered the concept of smart
contracts and opened the gates to limitless technological possibilities by offering a turing
complete system not just to transfer digital assets but beyond.

However, with a history of unstable and high volatility in prices of these cryptocurrencies the
dream of running a sustainable enterprise using cryptocurrencies is still a far cry. And thus,
stablecoins were invented to solve the above problem. As of writing this paper there exist over
200 stablecoin projects both in the active and under-development phases. Yet most of them
are not truely enterprise-friendly and reliable stablecoin that can replace fiat currencies in
digital transactions.

For Example: One of the biggest stablecoin failure is of UST stablecoin of Terra Luna which lost
99.99% of its ecosystem valuation (more than $40 billion in three days) after the UST stable
coin depegged. Even after knowing the problem beforehand Terra Luna ecosystem was not
decentralized enough to make amendments on these changes which were given by their
community.

Private issuers of stablecoin like USDT and USDC does not publish a complete transparent audit
report on their asset holdings which backs their claim that they have, with respective to, 1 US
Dollar to 1 USDT and 1 USDC, out of which USDT has only 5.81% of their treasury in cash and
bank deposits as per their March 2022 [report](https://tether.to/en/transparency/#reports), where USDC does not have any transparency on
their treasury holding [report](https://www.centre.io/hubfs/PDF/2022%20Circle%20Examination%20Report%20March%202022.pdf?hsLang=en). This is a major issue as the decentralized ecosystem should not
use centralized stablecoin by private issuers which deceives the purpose of true
decentralization as they can control and manipulate the supply of their stablecoin without
consulting with the user community or through community governance.

## Overview

To create a stablecoin that meets the requirements of businesses and enterprises, it is
important that not only is it competent enough against traditional solutions but also presents
significant improvements over them. We offer USDAO stablecoin as a solution to the above
problem statement. USDAO stablecoin has been designed to keep simplicity, interoperability,
and business compatibility at its core.

Integrating USDAO as a payment channel into your existing business or enterprise use case is
simpler than the leading payment solutions available today. All you need is a blockchain wallet
with an account to send and receive payments in USDAO to get started. The process is simpler
compared to traditional solutions which include registrations, KYC (Know Your Customer),
complex integrations, and high transaction fees.

Unlike many other existing stablecoins like USDT and USDC (USD Coin), we offer 100%
transparency in accountings and a robust governance mechanism that shall be fully
decentralized and run by an open community. We have also removed the unfair and
unnecessary burden of overcollateralization mechanism of assets for minting tokens as DAI
does. Instead, we bring a fairer and robust protocol to maintain pool stability. The USDAO pool
mechanism assures that the pool never gets undercollateralized and users are never
threatened with forced liquidation.

Above all, unlike its competitors, USDAO comes up with an ecosystem of in-house native use
cases. The USDAO stablecoin is one crucial element to the financial architecture we are
building. The details of such use cases are mentioned in the respective sections below. With
the presence of USDAO on multiple blockchains and combining its interoperability and
compatibility, it becomes a one-stop destination for truly decentralized robust, safe, and secure
financial solutions that is industry ready.

Before moving onto USDAO workflow let’s dive into some of its crucial components and
terminologies. The project is inspired from the USM project. However, we’ve made significant
changes and added multiple components to meet our requirements.

All prices are denominated in ethereum. These prices are computed by consulting ETH/USD
price oracles, except when otherwise stated. Since the stablecoin is deployed on multiple
blockchains the keyword ERC20 is used in a general form. Every such statement is true for all
the other protocols like BEP20 for Binance Smart Chain and other chains respectively.

## Components & Terminologies

The contracts are designed in a way to reward minting while discouraging burning. The output
can however still affect, depending upon how much “change” minting or burning of USDAO is
bringing on the collateral reserve. So, in the case of USDAO minting, the tokens minted within
the 5% range of “change in total collateral” results to 1:1 output. Whereas burning USDAO can
cause slippage depending upon the number of tokens being burnt.

For detailed technical analysis please checkout https://docs.usdao.io/usdao-v2/.

### USDAO

This is the actual stablecoin whose price is pegged relatively to 1 US dollar. It can be minted
using Ether. The amount of tokens minted depends upon the median ETH/USD price returned
by the oracles which is used by the system at the time of the transaction.

### ASSET

ASSET Token is the governance token of the protocol aimed to distribute governance
rights/voting rights for the USDAO Ecosystem. ASSET can be acquired by participating in the
sale of tokens through a USDAO community campaign/Launchpads or by earning the reward
for staking the USDAO stablecoin in [OnVault](https://docs.usdao.io/usdao-v2/protocol/onvault-borrowing-and-staking-protocol) feature of USDAO ecosystem.

97% of the funds raised by the ASSET governance token sale would be deposited into the
USDAO Pool to further stabilize USDAO Pool and the remaining 2% for the liquidity pool pair
creation and 1% towards Community Marketing.

## USDAO Pool

The Ether that is deposited during the minting operation of USDAO stablecoin and the ETH
deposited for borrowing of USDAO stablecoin from OnVault feature in USDAO Ecosystem is
deposited into the USDAO smart contract, also known as the USDAO Pool. The USDAO Pool is
the backbone of the entire system as it determines the financial health of the system. It helps
determine the debt ratio.

The funds raised from the ASSET Token sale will be locked in the USDAO pool to create deep
liquidity which will stabilize USDAO stablecoin at 1 US dollar.

## Buffer

Buffer is the Ether value in USD calculated using oracle price which is left after subtracting
USDAO total supply in the ecosystem. For more understanding: review our [docs](https://docs.usdao.io/usdao-v2/)

## Mint Price

Mint price is the price at which USDAO stablecoin is minted against Ether. It is relatively pegged
to 1 US dollar worth of Ether. The price of $1 worth of ETH at the time of minting is
determined by the median of ETH/USD price returned by the oracles being used.

The mint price is not subjected to fluctuation from its base price of $1. This is intentional and is
important to discourage any arbitrage opportunities.

## Burn Price

Burn price is the price at which the user withdraws back his Ether against the deposited
stablecoins. Equivalent to the minting price, the burn price is decided by the current ETH/USD
prices returned by the oracles in the USDAO Ecosystem.

### Debt Ratio

In its simplest mathematical representation, the debt ratio can be defined as the ratio of the
total number of stablecoins out in the market to the US dollar value of the USDAO pool i.e.

> 𝐷𝑒𝑏𝑡 𝑟𝑎𝑡𝑖𝑜 = 𝑡𝑜𝑡𝑎𝑙 𝑈𝑆𝐷𝐴𝑂 𝑠𝑡𝑎𝑏𝑙𝑒𝑐𝑜𝑖𝑛𝑠 𝑖𝑛 𝑡ℎ𝑒 𝑚𝑎𝑟𝑘𝑒𝑡 / 𝑈𝑆𝐷 𝑣𝑎𝑙𝑢𝑒 𝑜𝑓 𝑡ℎ𝑒 USDAO P𝑜𝑜𝑙

The debt ratio signifies the ratio of the amount of buy and sell activities of USDAO stablecoin in
the market. In other words, if the debt ratio is, let’s say, 50% that is equivalent for every 100
USD worth of Ether present in the system there are 50 stablecoins (worth 50 USD) out in the
market. This also means that each token if burnt right now for Ether the system has sufficient
collateral in the pool to pay every USDAO user back.

The debt ratio of 100% or above is an alarming situation for the system because it means the
system does not have enough Ether to return to users in case of 100% USDAO token
withdrawal. Hence at this stage, the users receive Ether which is in proportion to the number
of tokens they are withdrawing and the amount of Ether available in the pool.

As an example, let’s consider a situation where 1 Ether is 1 USD. Let’s suppose there are a total
of 100 USDAO tokens in the market. Now let’s assume a person owns 50 of them and he wants
to burn 50 USDAO tokens. If the debt ratio is below 100%, he shall receive Ethers worth 50
USD. But if the debt ratio is above 100% and only 80 USD worth of Ether is present in the pool
then the price of each USDAO reduces to 80 USD/100 USDAO i.e., 0.8 USD per USDAO. So, the
user shall get about 40 USD worth of Ether after the burn.

In such situations, the debt ratio then must be brought down below by funding the USDAO
Pool by minting ASSET tokens through USDAO Ecosystem collected revenue through
community governance or by investors. The community must be proactive to ensure required
steps must be taken to keep the debt ratio below 80%.

## MAX Debt Ratio

When the debt ratio goes above 80% the revenue collected in USDAO Ecosystem would be
used to collateralise the pool through governance by the foundation proposal.


## Oracles

An oracle is a reliable source of ETH/USD price. Our system currently calculates the median
ETH/USD price from following oracles
- Chainlink ETH/USD.
- Uniswap v3 ETH/USDC TWAP.
- Uniswap v3 ETH/USDT TWAP.

These oracles are an indispensable part of the whole ecosystem as it determines the mint and
burn prices. The debt ratio is also determined by the prices returned by the oracles.

The reason to use three oracles is to protect the system against any malfunction or inaccuracy
in any individual oracle. The system calculates the median price returned by these three
oracles, which is further used in operations like mint, burn, etc.

## Predictive Collateralized ASSET Price (PCAP)

PCAP Represent an predictive price of Asset token from the USDAO pool in terms of Collateral
allocated in USDAO pool’s Buffer
> PCAP = Buffer/Total Circulating supply of ASSET Token

This predictive price is implemented because the funds raised from the asset token sale will be
locked in the USDAO pool forever and the collateral locked will be in ETH creating a minimum
ASSET price discovery in accordance with the USDAO pool (In theory).

## USDAO Ecosystem Revenue

While Minting and Burning, a marginal charges are collected by the ecosystem through smart
contracts. There are no charges on Transfer of USDAO between accounts. These are the following
charges that the system generates:

<b>USDAO Mint</b>: 0.0% of the transaction total deducted when exchanging ETH for USDAO.

<b>USDAO Burn</b>: 0.3% of the transaction total will be deducted when exchanging USDAO for ETH.

<b>USDAO Transfer</b>: 0.0% charges on the Transaction Fee

<b>OnVault Staking</b>: 0.1% of the claimed ASSET deducted whilst claiming staking rewards.

All the charges collected accumulate in the USDAO Revenue contract which are governed by the
ASSET token holder community. The community hence can decide how to utilize the funds
generated for the welfare of the ecosystem. The RUIT foundation, however, can also request a
marginal share of the fund from the USDAO governance community(ASSET) through proposals to
promote economic activities like running hackathons and other activities essential for uplifting
the USDAO ecosystem.

The percentage of all the above types of charges is decided by the ASSET governance community
through prescribed governance protocol.

## RUIT Foundation Revenue

The RUIT foundation receives working and operation capital from USDAO ecosystem revenue
through community governance, with the purpose being the ongoing operation and maintenance
costs required to meet, the costs of the base infrastructure which supports the USDAO protocol.

Only RUIT Foundation holds the key rights to propose the proposal for withdrawing the funds
from the USDAO Ecosystem Revenue with the approval of the governance community.

## RUIT Foundation Proposal Funding

The RUIT Foundation may request additional funds from the USDAO ecosystem to cover
additional activities beneficial to the protocol by submitting a budget proposal through the
governance proposal system.

Examples of budget proposals could include costs for running hackathons, additional liquidity
provision, marketing and so on.

To maintain neutrality and the principles of decentralized governance, the support of ASSET
token holders will be required to approve the proposal, meaning that the Foundation always
remains accountable to the wider community.

Any funds which would be transferred in the event of an approved proposal would be derived
from the USDAO Revenue contract’s collected revenue in the form of either USDAO or ETH.

## Architecture

The USDAO protocol consists of multiple smart contracts. The USDAO stablecoin, is an ERC20
token whose price is pegged to 1 US dollar. The second token, the ASSET token, is also an ERC20
token but its price may fluctuate depending upon the Market volatility in the Exchange price and
independent from USDAO pool.

The prime role of the ASSET token is to absorb all the market price volatility of Ether from USDAO
and help it maintain its original price which is pegged to 1 US dollar.

The entire system is governed by ASSET token holders. The ASSET token holders, play a key role
of USDAO governance in the hands of a decentralized community. The holders of governance
tokens can create, vote and delegate proposals forming a DAO (Decentralized Autonomous
Organization) for the stablecoin through [Snapshot](https://snapshot.org/#/usdaogov.eth).

This is explained in detail in the [governance section](https://docs.usdao.io/usdao-v2/decentralized-governance/usdao-governance-protocol) in the docs:

Apart from regular mint and burn operations users can also:
1. Stake USDAO stablecoin to get ASSET token as rewards for long-term holders. This is
possible through the staking mechanism provided by [OnVault staking](https://onvault.usdao.io/?#/stake).
2.  Borrow USDAO by providing Ether as the collateral on [OnVault App](https://onvault.usdao.io/#/dashboard) at 0% Free Interest
Rate on collateral, Close your Debt any time without incurring any Interest charges.
3. User’s will get ETH* and ASSET token in reward for Staking USDAO in USDAO Vaule.

## How it works

The USDAO stablecoin is designed to be pegged to 1 US dollar. The two operations, mint and
burn, help it maintain its peg. When either of these two activities increases more than the other,
the USDAO mint or burn price rises or falls slightly to discourage any more such operations.

However, ideally in stable market conditions, if a user deposits x dollar worth of Ether into the
system he shall receive x amount of USDAO stablecoins. Conversely, if a user deposits x amount
of stablecoins back into the system he shall receive x US dollar worth of Ether back in his wallet.

<i>The prices for all such operations are determined by the median price of following oracles</i>

<p align="right">- <i>Chainlink ETH/USD, Uniswap v3 ETH/USDC TWAP, Uniswap v3 ETH/USDT TWAP</i></p>

However, since the price of Ether is constantly volatile it is required to maintain the US dollar
value of the USDAO pool always greater than the number of stablecoins out in the market. This is
made possible by funding the pool by selling the ASSET Token which is the governance Token of
the system through community issuance/Launchpads and raise funds and supply it to the USDAO
pool to maintain the stability of the USDAO stablecoin and keep the system always financially
healthy.

ASSET token holders act as the governance community for the USDAO ecosystem. ASSET token
holders can create and vote on the proposals to make the USDAO protocol always pegged to US
dollar.

The exchange rate for the above operation is determined by a set of oracles. One of the biggest
hurdles in keeping the trade fair arises through irregular oracle prices. Differences in prices in the
USDAO system and the outside world may expose the entire system to unknown opportunities
for exploitation and arbitrage. To overcome this issue the protocol utilizes three popular and
reliable oracles -
1. Chainlink’s ETH/USD feed, sourcing a bunch of off-chain sources
2. A Uniswap v3 TWAP (time-weighted average price) vs a stablecoin: specifically, ETH/USDC.
3. Uniswap v3 ETH/USDT TWAP

Now even if one of the oracles stopped working or provided the wrong prices the system will
continue to work properly. Using the median of the three oracles, protect against malfunction by
any single oracle. The median value returned by the oracles is used for all the system's
calculations. Through governance, the community can add or delete oracles to make the USDAO
ecosystem more robust.

The USDAO protocol also has USDAO Pool contracts that hold the collateral (ETH) and other
features like secure transactions, which allows the protocol to prevent fraud from any party with
the use of strong cryptographic techniques which makes this protocol more secure and safe for
the public blockchain.

USDAO stablecoin can be used for everyday means of exchange, a store of value, market entry,
and most commonly to provide a less volatile holding ground for investors and traders during the
upswings and crashes of the cryptocurrency market.

## Advantages

- `Resourceful documentation, SDKs and tools, to build applications easily and elegantly on
top of the USDAO Ecosystem.`
We are providing rich content for the documentation,
libraries, and APIs along with tutorials to the developer community to build applications on
top of USDAO. The resources will be compatible with all the major programming languages
that are popular in blockchain development. This promises continuous innovation &
development of innumerous applications in the future.
- `Simplified integration and user-friendly tools.`
We have emphasized heavily keeping the
complexity of the applications away from the user experience. The applications and tools
built on USDAO stablecoin are remarkably simple to integrate into any web or mobile
application. All our applications are designed to be cross-OS platforms, cross-browser
platforms with minimal clicks and dependencies. We are also providing simple
documentation, video tutorials, and support to simplify the integration of our USDAO SDK
on your platform with minimal technical knowledge.
- `Robust architecture and a strong peg to 1 US dollar.`
The pooling mechanism is designed in
such a way to always grow in value without putting any financial pressure on either users
or investors. This ensures the stablecoin is always strongly pegged to 1 US dollar by
keeping the debt ratio always low. The system is also designed to keep a balance between
the number of mints, burns, and discourage too much arbitrage activity committed in a
short period. It is designed to keep the collateral position stronger irrespective of a market
bullish or bearish run.
- `Governed by a 100 percent decentralized community.`
Any person with ASSET governance
tokens has the right to create a proposal, vote, or delegate their votes, that can make
crucial changes depending on the future requirement through snapshot.
- `Presence in multiple blockchains.`
USDAO and its applications will be deployed in multiple
blockchains including Ethereum and others. As more improved and better blockchain
platforms emerge in the future we shall mark our presence there as well.
- `Available in multiple pairs and on all major exchanges.`
USDAO would be available in all the
major exchanges of the world including both centralized and decentralized exchanges. It
shall also be available in as many pairs as possible, notably ETH/USDAO, BTC/USDAO, and
many more.

# Fig. High-level overview of the project
## Detailed Comparison & Review of USDAO, USDT, USDC & DAI

| Features | USDAO | USDT | USDC | DAI | 
| --- | --- | --- | --- | --- |
|Market Cap(18-02-2022) | NA | $78,732,248,474 | $52,466,941,954 | $10,215,966,621 |
| Current Price(18-02-2022) | NA | $0.9996 - $1 |  $0.9999 - $1 | $0.9996 - $1 |
| Circulating Supply(18-02-2022) | NA | 78.73B USDT | 52.46B USDC | 10.21B DAI |
| Launch Date | NA | 2014 | 2018 | 2017 |
| All Time High | NA | $1.32 | $2.35 | $3.67 | 
| All Time Low | NA | $0.91 | $0.92 | $0.94 | 
| Live | Pre Launch | Yes | Yes | Yes | 
| Asset Backed/Algorithmic | Asset Backed | Asset Backed | Asset Backed | Asset Backed | 
| Crypto Reserve | ETH | USD, EUR, YEN | USD | ETH | 
| Underlying Asset | USD | USD | USD | USD | 
| Platform | Ethereum, BSC, Cardano, Algorand, Solana, OKExChain, Huobi Eco Chain, Avalanche, Elrond, Tron, Hadera Hashgraph, Polkadot (upcoming) | Ethereum BSC, Solan, Omni Protocol, EOS, Tron, Algorand | Ethereum | Ethereum | 
| Complexity | Medium | Low | Low | High | 
| Open Source | Yes | Hybrid | Hybrid | Yes | 
| Ecosystem | USDAO Community | Centralized | Centralized | MakerDAO | 
| Exchange ability | Yes | Yes | Yes | Yes | 
| Symbol | USDAO | USDT | USDC | DAI | 
| Minable | No | No | No | No | 
| Mintable | Yes | Yes | Yes | Yes | 
| Website | Usdao.io | Tether.to | Centre.io | Makerdao. | 
| Whitepaper | https://app.usdao.io/whitepaper | https://tether.to/wp-content/uploads/2016/06/TetherWhitePaper.pdf | https://f.hubspotusercontent30.net/hubfs/9304636/PDF/centre-whitepaper.pdf | https://whitepaper.io/document/588/dai-whitepaper | 
| Privacy (KYC) | No | - | - | No | 
| Collateral Type | Crypto Backed | Fiat Backed | Fiat Backed | Crypto Backed | 
| Ease Of Use | High | High | High | High | 
| Legal Name | USDAO Foundation | iFinex, Inc. | Circle Internet Financial Limited | MakerDAO Foundation | 
| Audit Frequency | Public Smart Contract | Infrequent | Monthly | Public Smart Contract | 
| Hardware Wallets | NA | Ledger, Trezor | Ledger, Trezor | Ledger, Trezor | 
| Exchanges | Bitmax, Poloniex, Kraken, Bittrex, Latoken,Coinbase, Kucoin, Probit, CEX (Centralized Exchange),Huobi Global, OKEX,Bitfinex, Kyberswap, Uniswap (upcoming) | Kucoin,Bitfinex, Binance, Poloniex, Okex, Gate.io, Bittrex Global, Kraken, Huobi Global,Bitmax, Binance US, KyberSwap, HitBTC, Bitcoin.com | Coinbase Pro, Binance, Poloniex, Kucoin, Bitfinex, Okex, Bitmax, Huobi Global, Gate.io, KyberSwap, IDEX, Uniswap, HitBTC, Oasis Trade, Krake | Bitfinex, Kucoin, KyberSwap, Radar Relay, Bittrex Global, Coinbase Pro, Kraken,Gate.io, IDEX, Uniswap, HitBTC, Oasis Trade | 
| Fees | Yes | - | - | Yes | 
| Backing Coins | 8(upcoming) | 3 | 1 | 1 | 
| Reserve | Yes | Yes | Yes | Yes | 
| Features | USDAO | USDT | USDC | DAI | 
| Stability | High | Medium | Medium | Medium | 
| Integration | High | High | High | High | 
| Ownership | Community Driven | Several Exchanges | CENTRAL | MakerDAO | 
| Gas Optimization|  Yes | No | No | No | 
| Flexibility | High | High | High | Medium | 
| Multi Blockchain Support | High | Medium | Medium | Low | 
| Decentralization | High | Medium | Medium | High | 
| Fund Freezing | No | Yes | Yes | No | 
| Scalability | High | High | High | Medium | 
| Liquidity | High | High | High | High | 
| Transparency | High | Medium | Medium | High | 
| Security | High | Medium | Medium | High | 
| Automation | High | Low | Low | Medium | 
| Wallet Support | High | High | High | High | 

## Decentralized Governance - Snapshot
### Understanding Snapshot
Snapshot is at the forefront of innovating DAO participation by creating equitable and
customizable participation structures across all DAOs for creating proposals, discussion, and
voting. Snapshot helps Decentralized Autonomous Organizations to facilitate smooth and
seamless financial transactions worldwide in a decentralized manner.

Snapshot has become widely popular among many DAO communities in the past year, which is
used mainly as an off-chain multi-governance framework that enables gasless voting for DAOs
while creating, and voting on proposals, which means the protocol doesn’t cost any precious
ETH.

### Key Feature
- Creating a proposal and voting for free.
- Flexible voting strategies: vote with ERC20s, NFTs, or any contract.
- Multiple voting systems: single choice, approval voting, quadratic voting and more.
- Snapshot Spaces can have their custom skin and domain name.
- Fully open source with GPL-3.0-or-later and MIT license.

### Strategies in Snapshot
A strategy is a JavaScript function which is used to return the score for a set of addresses.
Strategies are often used on Snapshot to calculate the end result for a proposal. A proposal can
have a single or multiple strategies. The default strategy in Snapshot is to calculate the balance of
an ERC20 for each voter.

As per the Snapshot we have to add a voting strategy for our proposals. erc20-balance-of and
Contract-call are the most used strategies. Here we can have multiple strategies and we can add
custom strategies as well. We can add up to 5 strategies in our space.

Here we added our own customized token and there is a feature of editing the strategy by
clicking on it once selected.

### Voting types in Snapshot
Snapshot supports a number of different voting types and they even plan to support many more
in the future. It follows a distinct mechanism to ascertain the voting power of each vote. The
voting power of each vote can be calculated via the strategy selected in the proposal by the
voter.

1. Single Choice Voting - Under this system a voter can choose a single option among the various
choices available to him. Under this case, the entire voting power would go to the selected
choice.
2. Approval Voting - In this case, each voter can approve any number of choices and every
selected choice would be given equal voting power.
3. Quadratic Voting - Herein, each voter may disperse his voting power across any number of
choices and the results would be calculated quadratically.
4. Ranked Choice Voting - This is the most interesting voting type present in Snapshot. Here, each
voter can rank any number of choices. Votes are initially counted for each voter's top choice.

### How to create Proposal in Snapshot
In order to create a new proposal on Snapshot follow the below-mentioned steps
- Firstly, go to any project space and click on connect wallet in the top right corner of the
window.
- Connect with wallet provider where you hold relevant tokens and thereafter click on “New
Proposal”
- Fill out the Title and summary of your proposal. Mention all the required details.
- Go to the “Actions” box and select the Voting Type, start date and end date of your proposal.
This would be the time period available to the users to vote for your project. Make sure you allow
enough time frame for voting.
- Use the default Snapshot block number or you can change it as per your requirements. The
block number is the snapshot where the balance of voters will be counted.
- Here comes the final step! Just click on “Publish” and your proposal is created!

### We are also looking up to do the setup of Orange
Orange (Le Vote)- Here, Each vote is encrypted using a new encryption mechanism before
submission.
- For each encrypted score in the vote, proofs are generated and stored. Everyone can use
these proofs to verify the correctness and the eligibility of each submission without
decrypting the content of the vote.
- This ensures the validity of the submitted votes in the counting process and at the same
time it also maintains confidentiality.
- As this voting solution is based on blockchain, it secures the organization and results of a
poll.
- Le Vote guarantees the secrecy of the vote by using a transparent and anonymous
mechanism without any personal data being stored in the databases of the service
providers and app developers.

## OnVault - Introduction to 0% Interest free Borrowing
OnVault is a decentralized borrowing protocol that allows you to draw interest-free loans
against Ether used as Collateral. Loans are paid out in USDAO(a crypto backed stablecoin) and
need to maintain a minimum collateral ratio of 110%.

In addition to the collateral, the loans are secured by a Stability Pool containing USDAO
and by fellow borrowers collectively acting as guarantors of vaults created. Learn more about
these mechanisms in our documentation.

OnVault as a protocol is non-custodial, immutable, and governance-free.
### OnVault Terminology
- <b>Collateral</b>: Collateral is any asset which a borrower must provide to take out a loan, acting
as a security for the debt. Currently, OnVault only supports ETH as collateral.
- <b>Debt</b>: Amount of USDAO that the user borrows against the collateral.
- <b>Vault</b>: The position of ETH-USDAO created in the system when ICR > MCR.
- <b>TCR</b>: The Total Collateral Ratio is the sum of the collateral of all Vaults expressed in US
Dollar, divided by the debt of all Vaultsexpressed in USDAO.
- <b>MCR (Minimum Collateral Ratio)</b>: The minimum collateral ratio is the lowest ratio of debt
to collateral that will not trigger a liquidation under normal operations (aka Normal Mode).
This is a protocol parameter that is set to 110%
- <b>ICR (Internal Collateral Ratio)</b>:Value of Collateral in USD / Number of USDAO borrowed
- <b>CCR (Critical Collateral Ratio)</b>: CCR is when the TCR of the USDAO Pool falls below the
125%.
- <b>Recovery Mode</b>: When the USDAO Pool reaches CCR, then the system is said to be in
Recovery Mode.
- <b>Fees</b>: There is a one-off fee (0.7%) whenever USDAO is borrowed.
- <b>Staking</b>: Users can deposit the USDAO Stablecoin in the OnVault Staking to earn interest
and other benefits.
- <b>ASSET</b>: The incentive token generated to Stability Providers for staking USDAO. ASSET
token is rewarded as per Quater-Life method to incentivise early adopters.
- <b>Stability Pool</b>: Onvault Staking funds are collected in Stability Pool is the first line of
defense in maintaining system solvency. It achieves that by acting as the source of liquidity
to repay debt from liquidated Vaults—ensuring that the total USDAO supply always
remains backed.
- <b>Liquidation</b>: To ensure that the entire USDAO supply remains fully backed by collateral,
Vaults that fall under the Minimum Collateral Ratio of 110% in the normal scenario, and
when in Recovery Mode the Minimum Collateral Ratio of 125% will be liquidated (closed).
- <b>Liquidator</b>: The address that calls Liquidation function.

### General Motivation:
#### What’s the motivation behind OnVault?
Stable-value assets are an essential building block for Ethereum applications and have grown to
represent tens of billions of dollars in value.

However, the majority of the asset value is in the form of fiat-collateralized stablecoins like USDC
and Tether. Decentralized stablecoins like DAI and sUSD make up only a small portion of the total
stablecoin supply, meaning the majority of stablecoins are centralized and controlled by private
issuers.

USDAO being a decentralized, transparent community driven and 100% crypto-backed stablecoin.
So USDAO came up with a solution like OnVault which addresses this issue by creating a capital
efficient and user-friendly way to borrow stablecoins. Furthermore, OnVault is governance-free,
ensuring that the protocol remains completely decentralized.

#### What are the key benefits of OnVault?
OnVault’s key benefits include:
- 0% interest rate — as a borrower, there’s no need to worry about constantly accruing
debt.
- Minimum Collateral Ratio of 110% — more efficient usage of deposited ETH
- Fully decentralized — OnVault contracts have no admin keys which means there are no
admins to change anything in the contracts.
#### Can OnVault be upgraded or changed?
No. OnVault has no admin key, and nobody can alter the rules of the system in any way. The
smart contract code is completely immutable.
#### What are the main use cases of OnVault?
1. Borrow USDAO against ETH by opening a Vault.
2. Secure OnVault by providing USDAO to the Stability Pool in exchange for rewards in
ASSET Token.
#### What do I need in order to use OnVault?
To borrow USDAO, all you need is a wallet (e.g. MetaMask) and sufficient Ether to open a Vault
and pay the gas fees.

To become a Stability Pool depositor , you need to have USDAO tokens. USDAO can be borrowed
by opening a Vault or by minting with Ether from the USDAO pool. You can also use CEX or DEX
where USDAO is listed inorder to buy USDAO.
#### Does OnVault charge any fees?
There is a one-off fee whenever USDAO is borrowed.
The fees cannot become smaller than 0.7% on Borrowing amount of USDAO.
When the system is in Recovery Mode, there is no Fee for Borrowing USDAO.
#### How can I earn money using OnVault?
To generate revenue using OnVault is by depositing USDAO to the Stability Pool (staking USDAO)
and earn liquidation gains (in ETH) and ASSET in rewards.
#### Can I lose my funds?
As a non-custodial system, all the tokens sent to the protocol will be held and managed
algorithmically without the interference of any person or legal entity. That means your funds will
only be subject to the rules set forth in the smart contract code.

There are two scenarios under which you may lose a part of your funds:
- You are a borrower (Vault owner) and your collateral in ETH is liquidated. You will still
keep your borrowed USDAO, but your Vault will be closed and your collateral will be
used to compensate Stability Pool depositors(Stakers).
- You are a Stability Pool depositor(Stakers) and your deposited USDAO is used to repay
debt from liquidated borrowers. Since liquidations are triggered any time borrowers’
collateral drops below 110%, you will receive more ETH in return with a very high
probability. However, if ETH decreases in price and you maintain exposure, you may
lose value in your total pool deposits.
### Borrowing
#### Why would I use OnVault for borrowing?
OnVault protocol offers interest-free loans and is more capital efficient than any other borrowing
protocol (i.e. less collateral is needed for the same loan). Instead of selling Ether to have liquid
funds, you can use the protocol to lock up your Ether, borrow against the collateral to withdraw
USDAO, and then repay your loan at a future date.

For example: Borrowers speculating on future Ether price increases can use the protocol to
leverage their Ether positions, increasing their exposure to price changes. This is possible
because USDAO can be borrowed against Ether, sold on the open market to purchase more Ether
— rinse and repeat.*

<i>*Note: This is not a recommendation for how to use OnVault. Leverage can be risky and should be used only by those with
experience( an upcoming implementation in the USDAO Ecosystem).</i>
#### Why should a protocol offer interest-free borrowing?
The protocol charges one-time borrowing fees.
Other systems (e.g. MakerDAO) require variable interest rates to make borrowing more or less
favorable, but they do so implicitly that borrowers would not feel the impact upfront. Given that
this also needs to be managed via governance, OnVault instead opts for a fully decentralized and
direct feedback mechanism via one-off fees.
#### How can I borrow with OnVault?
To borrow you must open a Vault and deposit a certain amount of collateral (ETH) to it. Then you
can draw USDAO up to a collateral ratio of 110%. A minimum debt of 500 USDAO is required.
#### What is a Vault?
A Vault is where you take out and maintain your loan. Each Vault is linked to an Ethereum
address and each address can have just one Vault. If you are familiar with Vaults or Collateralised
Debt Positions(CDPs) from other platforms, Vaults are similar in concept.

Vaults maintain two balances: one is ETH acting as collateral and the other is a debt denominated
in USDAO. You can change the amount of each by adding collateral or repaying debt. As you make
changes in the balance, your Vault‘s collateral ratio changes accordingly.
You can close your Vault at any time by fully paying off your debt.
#### Do I have to pay fees as a borrower?
Every time you draw USDAO from your Vault, a one-off borrowing fee is charged on the drawn
amount and added to your debt. Please note that the borrowing fee of 0.7% is applicable under
normal operation. The fee is 0% during Recovery Mode. A 200 USDAO Liquidation Reserve charge
will be applied as well, but returned to you upon repayment of debt.
#### How is the borrowing fee calculated?
The Borrowing fee is added to the debt of the Vault, and the confined borrowing fee for USADO
OnVault is 0.7%.

For example: The borrowing fee stands at 0.7% and the borrower wants to receive 4,000 USDAO
to their wallet. Being charged a borrowing fee of 28.00 USDAO, the borrower will incur a debt of
4,228 USDAO after the Liquidation Reserve and issuance fee are added.
#### When do I need to pay my loan back?
Loans issued by the protocol do not have a repayment schedule. You can leave your Vault open
and repay your debt any time, as long as you maintain a collateral ratio of at least 110%.
#### What is the collateral ratio?
This is the ratio between the Dollar value of the collateral in your Vault and its debt in USDAO.
The collateral ratio of your Vault will fluctuate over time as the price of Ether changes. You can
influence the ratio by adjusting your Vault’s collateral and/or debt — i.e. adding more ETH
collateral or paying off some of your debt.

For example: Let’s say the current price of ETH is $3,000 and you decide to deposit 10 ETH. If you
borrow 10,000 USDAO, then the collateral ratio for your Vault would be 300%.

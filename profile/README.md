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

### USDAO Pool

The Ether that is deposited during the minting operation of USDAO stablecoin and the ETH
deposited for borrowing of USDAO stablecoin from OnVault feature in USDAO Ecosystem is
deposited into the USDAO smart contract, also known as the USDAO Pool. The USDAO Pool is
the backbone of the entire system as it determines the financial health of the system. It helps
determine the debt ratio.

The funds raised from the ASSET Token sale will be locked in the USDAO pool to create deep
liquidity which will stabilize USDAO stablecoin at 1 US dollar.

### Buffer

Buffer is the Ether value in USD calculated using oracle price which is left after subtracting
USDAO total supply in the ecosystem. For more understanding: review our [docs](https://docs.usdao.io/usdao-v2/)

### Mint Price

Mint price is the price at which USDAO stablecoin is minted against Ether. It is relatively pegged
to 1 US dollar worth of Ether. The price of $1 worth of ETH at the time of minting is
determined by the median of ETH/USD price returned by the oracles being used.

The mint price is not subjected to fluctuation from its base price of $1. This is intentional and is
important to discourage any arbitrage opportunities.

### Burn Price

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

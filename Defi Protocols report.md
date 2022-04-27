
## PART 1 - ETHEREUM


### Problem addressed - tokenomics - innovation - white paper - team - fundraising


---


## Lending protocols


### Makerdao


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>2014
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>100-150 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Rune Christensen
   </td>
  </tr>
  <tr>
   <td>Total funding raised
   </td>
   <td>54.5 million usd
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Tellor, Ramp, Coindirect, Consensys (Convertible note), Harbor (Debt Financing), Multis
   </td>
  </tr>
</table>



### Mechanism:

It is a protocol allowing the escrow of coins and taking out a loan in DAI, which in turn is “soft-pegged” to the US dollar. This allows for hedging against instability or for regular usage based on dai’s stability. A dai is generated against collateral stored in a vault. This collateral must be 150% the value of the DAI being taken out. This is to mitigate the risk of sudden drops in the collateral currency’s value, which would cause DAI to be under-collateralized. This would reduce investor confidence and drive down the value of DAI. So a significant motive for token holders is to keep the tokens over-collateralized. 

The value of DAI, rather than being left to natural market forces, is instead pegged to the USD through the usage of interest on loans (called stability fee) and interest on deposits (called dai savings rate). Manipulating these interest rates allows for controlling the price of dai. Changes in these rates involve consensus votes from MKR token holders (MKR is the governance token for MakerDAO).

An alternative system (not used for dai) is the Target Rate Feedback Mechanism (TRFM). This system functions on the basis of a target rate, which is the rate of growth/decline required for the dai price to match USD price. When the value of USD (target price) exceeds the current market price of DAI, the price of DAI is adjusted against ethereum collateral in the vault. To prevent liquidation, vault owners then can choose to either add more collateral, or to repay their debts. Repaying debts by buying DAI is a good option because the vault holder is able to take advantage of the dai’s undervalued price (since market price &lt; target price). Thus buying dai is incentivized.

Currently, over half of the collateral in the system is actually USDC and not ethereum. This is because the community is more interested in using stablecoins due to their price reliability. Since USDC is centrally regulated (by coinbase), this means that DAI is now mostly backed by the USD itself. But unlike Tether or USDC, this happens on a decentralized platform with complete transparency.


### Establishment and Fundraising:

Dai token and its smart contracts were officially launched on the Ethereum blockchain on Dec. 18, 2017. Venture capital firm Andreessen Horowitz invested $15 million in MakerDAO in September 2018, making it the owner of 6% of the total MKR token. That year, even as ETH saw a drastic drop in price, Dai managed to successfully maintain its $1 handle. 

In 2019, there were divisions within MakerDAO because founder Christensen wanted to create a more favorable environment to allow for assets besides cryptocurrency to serve as collateral for Dai. After some discussion, the Chief Technical Officer (CTO) left MakerDAO.


### Compound


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>August 2017
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>100-150 million usd
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Robert Leshner, Geoffrey Hayes
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Total funding raised
   </td>
   <td>33.2 million usd
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Chapter One ventures, DHVC, Andreessen Horowitz, Bain Capital Ventures, Coinbase Ventures, Polychain, Paradigm, New Form Capital,
   </td>
   <td>
   </td>
  </tr>
</table>



### Mechanism:

A lending and borrowing platform, compound’s major innovation was the introduction of the COMP token. The platform allows users to borrow any ERC-20 asset by keeping any other ERC-20 asset as collateral. The amount of collateral needed is specific to the volatility of the particular currency. So stablecoins require a smaller collateralization ratio compared to other crypto. Users can deposit multiple coins as collateral and the total collateralization is calculated from a weighted average. For example, if a user deposits 100$ DAI (which has collateralization factor 90) and 200$ ETH (which has cf 60). So the total required collateral ratio would be calculated as: 100/(0.66*60 + 0.33*90) = 1.443 or 144%

All tokens in the same pair market are pooled together and borrow/savings rates are the same for each market. 



* Borrow rate: Set using utilization ratio, slope and base rate. The borrow rate changes as new investors/borrowers act. In compound, this borrow rate follows a linear curve with utilization ratio as the x-axis. For example, if the liquidity pool is $100 million and a user borrows $25 million, then utilization rate is 25%. Assuming a base rate of 4% and slope of 10%, borrow rate calculated as: (0.25*0.1)+0.04 = 6.5%
* Supply (interest) rate: Borrow rate * utilization ratio - reserve pool. The supply rate is determined from the total interest earned by the protocol from lending minus a fraction which is sent to a reserve pool (to be used in cases of under collateralization). 

The main uses of compound are to create a leveraged long or short position. This allows for multiplying gains from price changes. Compound also features cTokens, which are tokens generated based on a user’s contribution to the collateral pool. These cTokens can themselves be traded or used for collateral in other DEFI markets. The ratio of cTokens to collateral (ex 1 cDai = x Dai) increases when interest accrued causes the value of collateral to increase.

Version 3 introduces the ability to supply liquidity in a custom range. **This idea is similar to the “limit order system” in traditional finance. **


### Establishment and fundraising

Compound has been financed through equity deals in multiple rounds. It raised an $8.2M seed round in May of 2018, led by industry giants including Andressen Horowitz, Polychain Capital, Coinbase Ventures and Bain Capital Ventures. Compound raised a $25mil Series A. The Series A was led by popular investors a16z, Paradigm, Bain Capital ventures and Polychain Capital. Compound said it doesn’t have a clear business model yet but this recent raise will give the company plenty of time to sustain itself for now.


### Aave


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>May 2017 (as Aave in 2020)
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>100-150 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Stani Kulechov
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Maven 11 Capital, Blockchain, SWS Venture Capital, Three Arrows Capital, Framework Ventures, ParaFi Capital
   </td>
  </tr>
</table>



### Mechanism:

Aave (which means ‘ghost’ in Finnish) began as ETHLend, founded by Stani Kulechov in 2017. Aave issues two different tokens, aTokens and AAVE tokens. The AAVE token is the native token of the Aave ecosystem and functions as both a governance and exchange token that offers users discounts on fees when using the protocol. aTokens are tokens that are given to lenders so they can receive interest on their deposits. As of the 4th March 2022, Aave is the #54th largest cryptocurrency by market capitalization.

Aave supports over 20 different assets, while Compound supports only 11. The protocol also offers stable interest rates, while Compound does not. Aave also introduced several pioneering features such as flash loans and delegated collateral vaults, both of which are the only types of loans that need not be overcollateralized by the recipient. Besides this, 80% of the fees earned are used to buy up and burn AAVE tokens. At Compound, reserves are currently created from the revenues, which are managed by governance. This benefits AAVE users by deflating their tokens and increasing its price.


### Establishment and fundraising

Aave began as ETHLend in 2017 after it raised $16.2 million in an Initial Coin Offering (ICO) to create a decentralized peer-to-peer lending platform. Later, they rebranded to Aave when they switched to a liquidity pool model. Aave launched the Aave Protocol in 2020, an open-source and non-custodial liquidity protocol where users can earn interest on deposits and borrow assets.


## Decentralized exchanges


### Uniswap


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>November 2018
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>44-68 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Hayden Adams
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Ethereum foundation, Union Square Ventures, Andreessen Horowitz, SV Angel, Version One, A Capital, Paradigm, Variant, ParaFi Capital
   </td>
  </tr>
</table>



### Mechanism:

It operates using a constant product Automated market maker. Users are able to provide liquidity to pairs in exchange for a uni token and rewards. When liquidity providers add to a pool, they receive newly minted liquidity tokens (UNI) entitling them to their proportion of the total pool as well as the 0.3% fee generated off each trade. These tokens are not speculative and simply keep track of how much of the pool is owed. Liquidity providers need to supply both assets in the same proportion they are currently at, otherwise, they will change the ratio and thus price.

Anyone can create a market (i.e. liquidity pool) by supplying an equal value of ETH and an ERC20 token. Since it follows the invariant rule, there is some slippage (lost money) when swaps occur between uncorrelated currencies (as opposed to correlated pairs like USDC/DAI). This slippage is even higher in pair markets with low liquidity. However this fact also allows for the existence of arbitrage opportunities which is a common use case of uniswap.

**Price Impact:** Since the price of a token is determined by the ratio of the two tokens in the pool, this changes during a transaction. When a swap is made against a pool the ratio of the tokens in the pool changes. This effect is stronger for low liquidity pools.

**Slippage:** This refers to the change in price that occurs while a transaction is pending. During this time, other swaps with higher gas fees may be executed resulting in a changed price.

**Impermanent Loss:** This is the loss faced by liquidity providers if when withdrawing their liquidity, the token ratio is different from when they deposited liquidity. The ratio of tokens in the pool will keep on changing based on the current market price. Arbitrageurs will trade with pools to match the pool token ratio (price) with that of the larger market. This rebalancing of the portfolio is risky for the LPs because when they decide to withdraw the funds the ratio might be very skewed in the direction of the token which has lost value. The loss is calculated as the difference between holding the tokens versus depositing them as liquidity in uniswap.

More on Uniswap V3: [https://kushgoyal.com/uniswap-v3-expalined-concentrated-liquidity/](https://kushgoyal.com/uniswap-v3-expalined-concentrated-liquidity/)

 


### Establishment and fundraising

Uniswap was born out of an idea proposed in 2016 by Vitalik Buterin for a decentralized exchange (DEX) that would employ an on-chain automated market maker with certain unique characteristics. A year later Hayden Adams began working on turning this idea into a functional product. After receiving several grants as well as $100,000 from the Ethereum Foundation, Uniswap launched in November 2018. The protocol quickly gained liquidity and started facilitating meaningful volume. Six months after launching, a fundraising round was completed, led by Paradigm to allow the addition of two more employees.


### Curve Finance


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>January 2020
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>
<ul>

<li>
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Michael Egorov
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Coinbase, Framework, Digital currency group, RRR ventures
   </td>
  </tr>
</table>



### Mechanism:

Curve was created (first as Stableswap) in November 2019 as a response to the slippage issue faced by users of decentralized exchanges such as Uniswap. This slippage, which results from price and liquidity volatility, can be greatly reduced when trading between stable or correlated pairs. This idea was developed into curve finance. Curve aims to help liquidity providers maximize return while also minimizing trader fees and reducing price slippage.

As of April 2022, Curve Finance has the highest total value locked among all defi protocols and supports many different blockchains. 


### Establishment and fundraising

First developed by Michael Egorov, who is also the founder and CTO of NuCypher, Curve saw significant TVl through 2020, breaking the 1 billion mark following the launch of their CRV governance token. Curve DAO has since faced several governance issues, including a governance attack by Yearn finance and accusations from the governance community about silencing and censorship. The investment details of Curve remain unknown. According to the founder, he obtained initial funds from established faces in the crypto industry.


### Balancer


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>November 2018
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>98-147 million usd
   </td>
  </tr>
  <tr>
   <td>Total funding raised
   </td>
   <td>30+ million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Fernando Martinelli, Mike Mcdonald
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Visary Capital, Inflection VC, Félix Fuertes, Nascent crypto, Accomplice, Placeholder, CoinFund, Inflection
   </td>
  </tr>
</table>



### Mechanism:

Balancer is a non-custodial automated portfolio manager, liquidity provider, and price sensor. The big idea of Balancer is, it is a new financial primitive that combines asset management and decentralized exchange. Balancer significantly improved upon the uniswap model by allowing up to 8 assets in single pools by using an invariant function that uses a bonding surface (rather than a bonding line in Uniswap’s x*y=k invariant function).


### Establishment and fundraising

BAL is used as a governance token over the network. It intended to provide the rights to make changes such as adding new assets or functionalities, modifying network parameters, or introducing a protocol level fee to allow the token to capture value. However, there is currently no defined structure for how this process will work.


### Symbiosis Finance


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>April 2022
   </td>
  </tr>
  <tr>
   <td>TVL
   </td>
   <td>7 million usd
   </td>
  </tr>
</table>



### Mechanism:

Symbiosis Finance aims to solve the problem of cross-chain swaps. They enable cross-chain swaps across any chain and any token pairs. Symbiosis achieves this by maintaining one single cross-chain liquidity pool for each pair of chains. This pool contains the two most liquid stablecoins from each chain. 

For example, the ethereum-binance pool contains the tokens USDC-BUSD. Essentially, when a swap is conducted, the transaction will be routed through other exchanges to get an equal value in that chain’s chosen stablecoin. This will then be swapped for the corresponding stablecoin in the destination chain and finally swapped again in a DEX of the destination chain to get the destination token which the user receives.

A relatively new protocol, Symbiosis Finance is likely to become a hub for a cross-chain enabled defi future.


![alt_text](images/image1.png "image_tooltip")


	_Figure: Symbiosis Finance swap pipeline_


## Derivatives protocols


### Opyn (Squeeth)


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>November 2018
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>44-68 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Hayden Adams
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Ethereum foundation, Union Square Ventures, Andreessen Horowitz, SV Angel, Version One, A Capital, Paradigm, Variant, ParaFi Capital
   </td>
  </tr>
</table>



### Mechanism:

The mechanism of squeeth works by matching shorts with longs through a perpetual contract. Shorters begin by staking ETH as collateral to withdraw oSQTH, and then short oSQTH by trading them on uniswap (with stablecoins). If the price of eth drops or rises too much, then their position is at risk of being liquidated due to disproportionately higher movement of oSQTH. In effect, the shorters bet against short-term volatility of eth and are rewarded with a funding rate (currently around 0.5%-0.9% per day, which comes to about 65% APY). Long holders are advised to only take such positions if they feel confident that eth price will go up in the short-term, because longer-term investments are made unprofitable by the funding rate. 

 building 


### Funding rate calculations

Funding rate is derived from the difference between market price and index price of squeeth.

**Squeeth:** Follows ETH^2 (derived from OSQTH and norm factor)

**OSQTH:** Market determined (uniswap)

**Index price of Squeeth: **ETH^2 price

**Mark price of Squeeth: **10,000*(oSQTH price in USD)/(normalization factor)

**Normalization factor:** A value used to scale down the value of OSQTH to pay in-kind funding

% change in normalization factor = % difference between squeeth price and ETH²

Consider an example where the normalization factor is 0.9 and we observe an average price over a month of 3000 for ETH/USD and $835.24 for oSQTH.

We calculate squeeth price by dividing by the normalization factor: 10000*835.24/.9 = 9,280,444.44. Then the funding is the percentage difference between the two prices (log ratio gives us this):

% change in normalization factor = % difference between squeeth price and ETH² = ln(9,280,444.44/3000²) = 0.0307

This means the funding rate is 3.07% for the 420 hour period and an approximate value of the new normalization factor is 0.872:

(new normalization factor) = (old normalization factor)*(1–0.0307) = 0.9*(1–0.0307)= 0.872

In this way the funding rate is set through demand and supply for the contract which will determine the distance between ETH² and the squeeth price. If it trades too far above, it will become attractive to mint oSQTH (and sell it) to receive a high rate of funding. If it trades too close to ETH² it will be unprofitable to short, and people will buy back oSQTH to repay their loans.

**Funding rate:** Rate of change in normalization factor. So for a constant funding rate, the normalization factor will decrease at a constant rate.


### Establishment and fundraising

Opyn was founded out of the apartment of founders Zubin Koticha and Aparna Krishnan, while in Berkeley. They met (third cofounder) Alexis in Berkeley Blockchain club, and decided to pursue their shared interest in something for the blockchain defi space. Because of a background in finance, Zubin was able to come up with the idea of hedging against risk in the defi space by the use of put options. The protocol initially functioned just as MakerDao did. An options seller stakes collateral to receive oeth. This oeth represents a put option where the holder can choose to exercise that option (sell at a certain price) regardless of market price. Consider an example where; an option that allows the holder to sell eth (currently priced $200) at $100 if the price of eth falls below 100 in 24 hours. If the probability of the price of eth falling below 100$ in 24 hours is ~ 1%, then the value of this option can be calculated by Possible profit x probability of eth falling below 100$ = 10$ x 0.01 = 10 cents. So in this case, the seller only has to put up $1 as collateral (against the 10 cents price of the option). 

However, over time, Opyn has transitioned away from its initial options offerings towards a combined options offering of squared ethereum (squeeth). Squeeth is a token indexed to the square of the underlying (ethereum). Holding squeeth plays out similar to a 2x leveraged position on eth, but with greater payoffs (due to convexity of squeeth returns) without the need to set strike prices or determine contract expiration dates.


### References



* [https://github.com/0xperp/awesome-squeeth](https://github.com/0xperp/awesome-squeeth)
* [https://medium.com/opyn/hedging-uniswap-v3-with-squeeth-bcaf1750ea11](https://medium.com/opyn/hedging-uniswap-v3-with-squeeth-bcaf1750ea11)
* [https://epicenter.tv/guests/zubin-koticha/](https://epicenter.tv/guests/zubin-koticha/) [Podcast-pre-squeeth]


### Opyn V2 (Gamma)


### Mechanism:

Opyn’s gamma protocol allows users to create and sell options that have the following benefits;



1. Options can be partially collateralized: This is achieved by calculating a margin _that is at least as much as potential losses incurred even in a Black Thursday like situation. _This means that a user can buy a put option for ETH @200 USD for only 10-20 USD. Then if the price of ETH falls below the strike price (200) at the expiry date, then the user can exercise their option and sell their ETH at the strike price to make a profit.
2. Collateralization using spreads (ex; a 400$ put option can collateralize a $300 call option)
3. Allows flash minting, which is a way to mint options first without collateral as long as the collateral is supplied within the same transaction. **This means users can mint and sell options first, and then add collateral in the same transaction**

Gamma options are cash settled, European options. Cash settled options are settled in the collateral asset, and option holders receive the difference between the price of the underlying asset at expiry and the strike price from option sellers. European options can only be exercised at the date of expiry. 

Selling options is a significant source of yield for users, with only the premium to lose. Other uses of options include hedging against downside risk (by buying a put option for example) and of course to leverage trade by putting in only margin as collateral but still being able to get exposed to potential upsides in full.


### Hedgic


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>Feb 2020
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Molly Wintermute
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Ethereum foundation, Union Square Ventures, Andreessen Horowitz, SV Angel, Version One, A Capital, Paradigm, Variant, ParaFi Capital
   </td>
  </tr>
</table>



### 
![alt_text](images/image2.png "image_tooltip")



### Mechanism:

Hegic is an on-chain **peer-to-pool** options trading protocol built on Ethereum. It allows users to purchase options or earn liquidity fees by providing liquidity to options. Hegic’s version of a put option is an on-chain contract that gives a buyer the right to swap their ETH for DAI at a specified price before the expiration date. Like other Hegic option contracts, an ETH put option buyer selects the amount, the period, and the strike price. The premium amount depends on the length of the contract (i.e. 1 month-long options are more expensive than 1 week-long options)

In Hegic, all writers share profit/loss. A writer simply stakes ETH/DAI to the pool. Profit/loss is distributed across the pool based on stake. Call writers provide ETH to the Hegic liquidity pool and begin earning an estimated 29% annual percentage yield (APY) on their money. The ETH provided will be used for selling call options. After providing ETH, a liquidity provider receives writeETH tokens. These are ERC-20 tokens that can be converted back to ETH whenever a liquidity provider wants to leave the pool. Similarly put writers also receive yield for providing DAI to the liquidity pool. DAI is used to sell put options. Hegic’s options are _American-style_, which means they can be exercised at any date before expiry.

The price of a Hegic option is the aggregate of a rate and a settlement fee. 
![alt_text](images/image3.png "image_tooltip")



### Synthetix


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>November 2018
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>44-68 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Hayden Adams
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Ethereum foundation, Union Square Ventures, Andreessen Horowitz, SV Angel, Version One, A Capital, Paradigm, Variant, ParaFi Capital
   </td>
  </tr>
</table>



### Mechanism:

Synthetix allows creating synthetic assets which are derivatives that track the underlying price of the asset through price feeds. Synths are collateralized by SNX tokens which are utility tokens provided by the protocol. Users stake SNX tokens to mint synthetic derivatives that track the price of ETH, USD, YEN and even GOLD and SILVER. 

To mint a synth, SNX stakers incur debt not in the amount, but as a proportion of the total debt of the pool. So, if a user stakes $1000 ETH in a pool of $20000 total size, then they will be responsible for 5% of the pool’s debt. If the price of ETH goes up _relative to other assets in the pool_, then this user will profit. This is because the total debt size will increase for everyone relative to their share, but the ETH they have staked will also grow in value, thereby making them a net profit.


### dydx


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>2017
   </td>
  </tr>
  <tr>
   <td>TVL
   </td>
   <td>1 billion usd
   </td>
  </tr>
</table>



### Mechanism:

Established in 2017 by a former coinbase engineer with extensive funding from seasoned crypto-investors, dydx launched with the promise of enabling margin trading on perpetual futures in a completely decentralized fashion. Currently, the dydx implementation on Layer 2 enables trading with no gas fees and low trading fees.

The dYdX Perpetual is a decentralized margin product that offers synthetic exposure to a variety of assets. The protocol only accepts USDC as collateral and all quotes are denominated in USDC. The protocol allows for taking up leveraged perpetual futures contracts. The minimum margin currently supported is 10% (implying max 10x leverage). 

Example; User buys a long perp for 1 BTC at current market price of 10,000 USDC. User does this at a 10% margin and so puts up collateral of 1000 USDC. So the user owes (short balance) 9000 USDC and is expected to buy 1 BTC (10,000 USDC). Let’s say BTC price appreciates by 10% so that 1 BTC = 11,000 USDC. Now, the user has a future for 11,000 USDC and only owes 9000 USDC. Now, the user can close the position and make a profit (received - owed - initially put up = 11000-9000-1000 = 1000 USD profit).

The minimum maintenance margin requirement is 5% and positions are liquidated by keepers if margin decreases below 5%. From our example, the keeper simply sells the BTC to pay back the short balance and keep the extra.

For a perpetual short position, the user commits to buying 1 BTC @ market price of 10,000 USDC (which is their negative balance) and commits to selling 1 BTC at strike price of 10,000 (which is a positive balance) by depositing a margin of 1000 USD. In this case, the collateralization ratio is 11000/10000 and therefore margin is (11000/10000 - 1) = 10%. If the price of BTC goes up by 5%, the margin becomes (11000/10500 - 1) = 4.76%, which causes the position to be liquidated.


## Yield protocol


### Ribbon Finance


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>8 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Julian Koh
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Paradigm, Nascent, Coindesk, Dragonfly, Ethereal, Scalar, Robot ventures, Alliances
   </td>
  </tr>
</table>



### Mechanism:

Ribbon Finance allows investors to earn yield returns through purchasing _structured products_. These products allow users to participate in ribbon protocol’s automated options strategies, such as betting on volatility, enhancing yields or principal protection. On ribbon, these are called _theta vaults_. Each theta vault corresponds to a specific strategy and particular asset.  Essentially, Ribbon allows users to earn yield through investments in underlying protocols such as Opyn on Ethereum and Zeta Markets on Solana.

 

There are two options strategies used in theta vaults;

1.Covered call: Guaranteed yield for foregoing upside of an asset. To reduce risk, vault automatically sells option regularly (i.e. weekly) and reinvests all earnings back into the vault. Past year has seen vaults earn 20-30% from options investments using this strategy.


    
![alt_text](images/image4.png "image_tooltip")


2.Put-selling: Put option contract allows holder to sell an asset at the strike price at a future date. Ribbon vaults creates put options by staking collateral and then sell these put options and earn a premium on them. Currently, 3 vaults offer put selling strategies.


### References



* https://www.linkedin.com/pulse/quantitative-analysis-defi-option-vault-strategies-samneet-chepal/


### Friktion


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>-
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>8 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Julian Koh
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Paradigm, Nascent, Coindesk, Dragonfly, Ethereal, Scalar, Robot ventures, Alliances
   </td>
  </tr>
</table>



### Mechanism:

Similar to ribbon finance, the friktion protocol allows users to invest in automated options strategies including covered call, put selling and more. Friktion, operates on the Solana chain, and calls its vaults _volts_. Similar to ribbon, each volt performs a specific strategy. It includes volts that perform crab strategies, hedging impermanent loss, etc.

The first volt which is also the main volt focuses on income generation through covered calls. It is a common strategy used by many DeFi vaults to earn sustainable yields.

Unlike traditional yield farming protocol that relies on token emission for yield, Friktion’s yield is derived from the option premium. It is more sustainable in the long run as the yield does not rely on token price.

 


### 


### 


### Convex Finance


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>November 2018
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>44-68 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Hayden Adams
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Ethereum foundation, Union Square Ventures, Andreessen Horowitz, SV Angel, Version One, A Capital, Paradigm, Variant, ParaFi Capital
   </td>
  </tr>
</table>



### Mechanism:

Th

 


### Establishment and fundraising


### Yearn Finance


<table>
  <tr>
   <td>Officially launched:
   </td>
   <td>November 2018
   </td>
  </tr>
  <tr>
   <td>Est. valuation
   </td>
   <td>44-68 million usd
   </td>
  </tr>
  <tr>
   <td>Founders
   </td>
   <td>Hayden Adams
   </td>
  </tr>
  <tr>
   <td>Investors
   </td>
   <td>Ethereum foundation, Union Square Ventures, Andreessen Horowitz, SV Angel, Version One, A Capital, Paradigm, Variant, ParaFi Capital
   </td>
  </tr>
</table>



### Mechanism:

Th. 

 


### Establishment and fundraising

O

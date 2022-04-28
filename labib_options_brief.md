**Meeting brief**

**Options pricing:**

If a stock price is more volatile(mostly random), then it follows normal distribution. According to this theory the price should move around ±34% of the current market i.e. 34% up or a 34% down. The chances of the price being in this 68% range are the highest. 

**Implied Volatility:**

Tall = Low Volatility & Short = High Volatility(Vega)

Vega(Implied Volatility) increases the option's price because higher chances of the option being in the money at expiration.

So, Sell options when IV is High

      Buy options when IV is Low 

**Call Option (Can be Bought):**



1. Loss limited to Option Price (Price at which the Option was bought)
2. Profit unlimited as the price may go up exponentially high
3. High Volatility makes this strategy appropriate
4. High IV = High Option price
5. Time decreases value at option

**Put Option (Can be Sold):**



1. Guaranteed sell of stock
2. Can be bought at a lesser price and if the price of the stock goes below the strike price, profit can be made because guaranteed selling price is confirmed
3. At the money - Buying an option at the current trading price
4. Out of money (A harder bet)
5. Loss incurred if - Market price at expiration > Strike price

**Call/Put Options**


<table>
  <tr>
   <td><strong>Long</strong>
   </td>
   <td><strong>Short</strong>
   </td>
  </tr>
  <tr>
   <td>Buy to open = Debit
   </td>
   <td>Sell to open = Credit
   </td>
  </tr>
  <tr>
   <td>Sell to close = Credit
   </td>
   <td>Buy to close = Debit
   </td>
  </tr>
</table>


**Option Pricing**


<table>
  <tr>
   <td>Intrinsic Value

<table>
  <tr>
   <td>Spot Price
   </td>
   <td>Strike Price
   </td>
  </tr>
</table>


   </td>
   <td>Time Value


<table>
  <tr>
   <td>Time to
<p>
Maturity
   </td>
   <td>Volatility
   </td>
   <td>Rate of 
<p>
Interest
   </td>
  </tr>
</table>


   </td>
  </tr>
</table>


We will have to stake on both sides of the market as the market can go either way. But we have to put the majority of it in the assumed profitable side so we can make a profit. Our ratio should be at least 60/40. If we put in 50/50 on both sides, we will be incurring the same amount of loss as of the gained profit.

**Payoff Range: **We will incur some amount of loss being on both sides of the market. We have to make a sufficient amount of profit to exceed the loss we incurred on the opposite side of the market. The range we have to exceed is called the payoff range, i.e. we will be making profit overcoming our losses.

**Crab Strategy: **When the market goes sideways i.e. there is no drastic change in the market then this strategy will make profit. The Crab Strategy is similar to selling a continuous straddle that resets periodically to be at-the-money.

**Different Volatility Prediction Models: **



1. Moving Average(MA)
2. Exponential Moving Average(EMA)
3. Auto-Regressive Conditional Heteroskedasticity(ARCH)
4. Generalized Auto-Regressive Conditional Heteroskedasticity(GARCH)
5. Auto-Regressive Integrated Moving Average(ARIMA)

**TVL: **Total Value Locked

**DTV: **Daily Traded Volume(Liquidity) - Increases Counterparty risk i.e. Low liquidity may lead to lack of counterparties. However, low DTV brings more alpha(profit)

Market Expectaion:



1. Crab - Price stable
2. Bull - Price goes up
3. Bear - Price goes down

## ML Team: 

Comes up with 



1. Market Expectation 
2. Volatility Prediction
3. Price Prediction

	Based on



* Inflation indexes
* Sentiment Analysis

Example: 
```
Elon Musk buys Twitter. He wants to buy the shares at 54$. Current price of shares in 34$.
So the price of shares will be increasing and will settle at a 80/20 range in between 34$ & 54$.
Because the deal may break and the price will fall back to its initial value.
```

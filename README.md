# Schrödinger's Coin Model

<a href="/static/pdf/Schrodingers_Coin_Model.pdf" download><button>Download PDF</button></a>

## Valuing Bitcoin as a Store of Value

### Introduction

Bitcoin has been compared to various forms of property and other assets traditionally used for storing value. In the absence of sound money, rational investors allocate capital to real estate, stocks, and other alternatives as stores of value. Inspired by ["Bitcoin as Property"](https://www.youtube.com/watch?v=mP0f2s39GDs) from Michael Saylor, this white paper discusses Bitcoin's potential to capture the monetary premium of traditional assets and its impact on their valuation.

### The Shift from Traditional Savings to Alternative Assets

Historically, less sophisticated investors saved their money in savings accounts, while more experienced investors sought leverage and efficiency through real estate and venture investments. During the last decade, with the decline in interest rates and the expansion of financial instruments, investors have turned to stocks, real estate, and exchange-traded funds (ETFs) as their primary stores of value.

The explosion of ETFs and the popularity of second investment properties or Real Estate Investment Trusts (REITs) have resulted in the monetization of numerous assets. By the end of 2021, many assets, including housing, were valued well beyond their utility values. Central banks, flooded with excess currency, have fundamentally broken the value of money, leading investors to seek assets that offer protection against the negative effects of money printing. This phenomenon has resulted in the financialization of the economy, where investors have no choice but to look for other forms of saving.

### Bitcoin: The Apex Asset for Monetization

Bitcoin has the potential to become the apex asset for monetization, consistently demonetizing traditional stores of value, such as currencies, bonds, real estate, equities, and gold.

Real estate is often considered a desirable asset due to its inherent utility value, but its value is also heavily influenced by monetization, which has created a situation where many people own multiple properties, driving up demand and prices. However, it's worth noting that owning property comes with its own set of issues. For example, property taxes and maintenance costs can significantly eat into any potential returns. Additionally, properties can depreciate over time, further eroding their value. Furthermore, despite owning a deed to a property, one does not actually own the property itself; the promise of ownership can be rescinded in certain circumstances. For instance, if the government decides to seize the property for public use, the property owner can lose their investment entirely. All these factors have led investors to consider alternatives for protecting their wealth, especially in a low-risk, low-inflation environment.

In contrast, Bitcoin offers a "building" that cannot be destroyed, requires no maintenance, and provides superior storage of value. As a decentralized, secure, and scarce digital asset, Bitcoin has the potential to capture the monetary premium of traditional assets, potentially leading to their demonetization.

Bitcoin is increasingly being recognized as a superior store of value for several reasons:

1. Scarcity: Bitcoin has a fixed supply of 21 million coins, creating a level of scarcity that protects its value from inflation.
2. Portability: Bitcoin is easily transferred and stored digitally, making it more practical than physical assets like gold.
3. Security: The decentralized nature of the blockchain technology underlying Bitcoin ensures its security and resistance to tampering.
4. Transparency: All transactions are recorded on the blockchain, creating a transparent and auditable record of ownership.
5. Accessibility: Bitcoin is accessible to anyone with an internet connection, making it an inclusive store of value.
6. Immutability or Censorship Resistance: The record of property ownership is secured by a massive and growing computer network, making it nearly impossible to alter or censor transactions. This provides an added layer of security and reinforces Bitcoin's status as a reliable and trustworthy store of value.

### The Model

The Schrödinger Coin Model is based on the concept of quantum superposition, where an object can simultaneously exist in multiple states until observed. In this case, Bitcoin is considered to have two possible outcomes: it either fails and it's worthless (the Dan Peña scenario) or successfully captures the monetary premium of traditional stores of value (the Saylor scenario).

Instead of relying on absolute certainty like in the scenarios above, this model assigns probabilities to each of them to arrive at a fair value for Bitcoin. If you open the box and observed a world where Saylor was right, what happened? What about when Dan was right?

### 1. Model Components

The model calculates the fair value of Bitcoin today using the following components:

a. **Asset Market Cap**: The current market value of each traditional store of value (e.g., gold, real estate, stocks, bonds).

b. **Monetary Premium Percentage**: The portion of an asset's market cap that is attributed to its status as a store of value.

c. **Probability of Capture**: The likelihood that Bitcoin captures the monetary premium of each asset.

d. **Time to Capture**: The expected time until Bitcoin captures the monetary premium of each asset. This can also be modeled as a vector with different captured percentages along time.

e. **Discount Rate**: The rate at which future expected capture values are discounted to present value to calculate today's fair value.

### 2. Model Calculation

Bitcoin's fair value is calculated as the sum of each asset's expected capture value:

$$
\left( \sum_{k=1}^n a_k \right)
$$

where each asset's fair value is defined as:

$$
a= \frac{(mcap) (mp) (prob)} {(1 + r)^n}
$$

- *mcap*: Current Market cap of each asset
- *mp*: Percentage of Market Cap that has monetization nature (not utility value)
- *prob*: probability of Bitcoin capturing this value
- *r*: discount rate
- *n*: number of periods until monetization is realized

Bear in mind that with this framework we could potentially also use today's Bitcoin price to calculate the current implied probability by the market.

### 3. Model Inputs

### Potential Asset Classes and estimated values - Data as of April, 2023

1. Stocks:
a. Market Value assumption: **$100T**
b. Source: Stock market capitalization can be sourced from the [World Bank](https://data.worldbank.org/indicator/CM.MKT.LCAP.CD) and [Statista](https://www.statista.com/statistics/710680/global-stock-markets-by-country/)
The data represents an approximate estimate, as the stock market capitalization varies with market movements.
2. Bonds:
a. Market Value assumption: **$130T**
b. Source: The global bond market capitalization was derived from sources such as the [Bank for International Settlements](https://stats.bis.org/statx/srs/table/f1.2). The data represents an approximate estimate, as the bond market capitalization changes with new issuances and redemptions. It only includes the total for "advanced economies".
3. Gold:
a. Market Value assumption: **$10T**
b. Source:The total market capitalization of gold was calculated using the [World Gold Council data](https://www.gold.org/goldhub/data/how-much-gold) on above-ground gold stocks and the average gold price per ounce at the time of writing. The data should be updated to reflect the current gold price for accurate valuation.
4. Silver:
a. Market Value assumption: **$1.3T**
b. Source: The total market capitalization of silver was estimated using the [Silver Institute data](https://www.silverinstitute.org/silver-supply-demand/) on above-ground silver stocks and the average silver price per ounce at the time of writing. The data should be updated to reflect the current silver price for accurate valuation.
5. Real Estate:
a. Market Value assumption: **$320T**
b. Source: [Savills Research](https://www.savills.com/impacts/market-trends/the-total-value-of-global-real-estate.html)
6. Cryptocurrencies (non-BTC):
a. Market Value assumption: **$500B**
b. Source: [Coinmarketcap.com](https://coinmarketcap.com/)

## Parallels to the Black-Scholes model for options valuation

The Black-Scholes formula is used to calculate the fair price of options, which are financial contracts that give the buyer the right (but not the obligation) to buy or sell an underlying asset, such as a stock or commodity, at a specified price and time.

The formula involves five inputs: the current price of the underlying asset, the strike price (the price at which the option can be exercised), the time to expiration, the risk-free interest rate, and the volatility of the underlying asset's price. Here's the formula for pricing of a call option:

$$
C = S*N(d1) - X*e^-rt*N(d2)
$$

The formula itself is a bit complex, but in simple terms, it works by estimating the probability of different future scenarios for the underlying asset's price, based on its volatility (how much its price tends to fluctuate over time). The formula then calculates the expected value of the option based on those probabilities, discounted to today's value using the risk-free interest rate.

The left side of the equation represents the value of the call option (the right to buy the underlying asset), while the right side represents the sum of the present value of the strike price (which is guaranteed if the option is exercised) and the expected value of the underlying asset's price at expiration. The expected value is calculated by multiplying the current price of the underlying asset by a probability density function, which is based on the volatility of the underlying asset's price.

One key difference between the two models is that the Black-Scholes formula is based on the assumption of continuous time and a known distribution of asset prices, while the Schrödinger Coin Model is based on the concept of quantum superposition, where an object can exist in multiple states until observed. The Schrödinger Coin Model assigns probabilities to each possible outcome to arrive at a fair value for Bitcoin, while the Black-Scholes formula uses a probability density function based on the volatility of the underlying asset's price.

Another difference is that the Black-Scholes formula is a closed-form equation, meaning that it can be solved analytically, while the Schrödinger Coin Model is a more complex model that involves multiple inputs and calculations.

Despite these differences, both models aim to estimate the fair value of an asset by taking into account various factors such as the current price of the asset, the time to expiration, interest rates, and volatility. Both models also consider the potential for extreme outcomes and the uncertainty of future events, which can contribute to the asset's volatility.

### Schrödinger's Coin and Volatility as a Feature, not a Bug

One of the most discussed aspects of Bitcoin and other cryptocurrencies is their inherent price volatility. In this section, we argue that the Schrödinger Coin Model explains the volatility of Bitcoin as a natural feature of its valuation, rather than a bug or a flaw. Furthermore, we will discuss how this volatility may decrease as we move closer to hyperbitcoinization.

1. **Extreme Outcomes**
The Schrödinger Coin Model is based on two extreme outcomes for Bitcoin: either it fails and becomes worthless (the Dan Peña scenario), or it successfully captures the monetary premium of traditional stores of value (the Saylor scenario). As a result, the model inherently predicts significant fluctuations in value depending on market sentiment and external factors that influence investors' perception of the likelihood of these outcomes.
2. **Small Changes in Probability, Large Changes in Fair Value**
Given the extreme nature of the two possible outcomes, small changes in the perceived probability of either scenario occurring can lead to substantial changes in Bitcoin's fair value. For example, a slight increase in the market's confidence in Bitcoin's success could result in a significant increase in its price, while a decrease in confidence could lead to a sharp decline.
3. **Uncertainty of Time**
Another factor contributing to Bitcoin's volatility is the uncertainty surrounding the time it takes to achieve hyperbitcoinization. During bull markets, the perception of time (t) tends to decrease as investors become more optimistic about Bitcoin's adoption and the speed at which it will capture the monetary premium of traditional assets. Conversely, during bear markets, the perceived time until hyperbitcoinization increases as market sentiment turns negative. This fluctuation in time perception adds another layer of volatility to Bitcoin's price.
4. **Decreasing Volatility as Hyperbitcoinization Approaches**
As we move closer to hyperbitcoinization, the volatility of Bitcoin is expected to decrease. This is because, over time, the market will gain more information about Bitcoin's adoption, regulatory environment, and technological developments. As a result, the market's perception of the likelihood of the two extreme outcomes will become more stable, leading to reduced price fluctuations.

In conclusion, the Schrödinger Coin Model explains the volatility of Bitcoin as a natural consequence of its valuation based on extreme outcomes, small changes in probability, and the uncertainty of time until hyperbitcoinization. As the market gains more information and becomes more confident in Bitcoin's future, its volatility is expected to decrease, tending towards zero. Understanding this aspect of the model can help investors make more informed decisions about the risks and rewards associated with investing in Bitcoin.

### Conclusion

The Schrödinger Coin Model provides a framework for valuing Bitcoin by considering its potential to capture the monetary premium of traditional assets such as real estate, stocks, and bonds. As a superior store of value, Bitcoin has the potential to consistently demonetize investment in traditional assets, leading to a shift in capital allocation and a reevaluation of their worth.

The model also sheds light on the inherent volatility of Bitcoin, which arises from the extreme outcomes, small changes in probability, and uncertainty of time until hyperbitcoinization. However, as the market gains more information and becomes more confident in Bitcoin's future, its volatility is expected to decrease, tending towards zero.

Furthermore, the model highlights the importance of understanding the risks associated with investing in Bitcoin, such as regulatory changes, technological challenges, and potential competition from other cryptocurrencies or alternative stores of value.

By understanding the dynamics of the Schrödinger Coin Model, as well as the factors contributing to Bitcoin's volatility and the associated risks, investors can make more informed decisions about the potential growth and risks associated with Bitcoin and other assets. This holistic approach to valuation enables a more comprehensive assessment of Bitcoin's potential as both an investment and a transformative technology.

# greeks


The Greeks are financial metrics that describe the sensitivity of an option's price to various factors such as changes in the underlying asset's price, volatility, time, and interest rates. These metrics are crucial for options traders and risk managers to understand how an option's price will change in response to market movements.


Delta (Δ):
Delta measures the sensitivity of the option's price to a change in the price of the underlying asset. For a call option, Delta is positive, and for a put option, Delta is negative.
Δ = ∂C/∂S
Where:
C is the option's price.
S is the underlying asset's price.
∂ denotes a partial derivative.
Δ ≈ 0.5 for at-the-money (ATM) call options.
Δ ≈ 1 for deep in-the-money (ITM) call options.
Δ ≈ 0 for deep out-of-the-money (OTM) call options.

Gamma (Γ):
Gamma measures the rate of change of Delta with respect to changes in the underlying asset's price. It shows how Delta will change as the underlying asset's price changes.
Γ = ∂Δ/∂S = ∂²C/∂S²
Gamma is highest for ATM options and decreases for ITM and OTM options.
High Gamma indicates that Delta will change rapidly with small movements in the underlying asset's price.

Theta (Θ):
Theta measures the sensitivity of the option's price to the passage of time, often referred to as time decay. It shows how much the option's price will decrease as the option approaches its expiration.
Θ = ∂C/∂t
Where:
t is time to expiration.
Theta is typically negative because, as time passes, the option's time value decreases.
ATM options have the highest Theta decay.

Vega (ν):
Vega measures the sensitivity of the option's price to changes in the volatility of the underlying asset. It shows how much the option's price will change with a 1% change in volatility.
ν = ∂C/∂σ
Where:
σ is the volatility of the underlying asset.
Vega is highest for ATM options and decreases as the option becomes ITM or OTM.
Higher volatility increases the option's price, so Vega is positive for both calls and puts.

Rho (ρ):
Rho measures the sensitivity of the option's price to changes in the risk-free interest rate. It shows how much the option's price will change with a 1% change in the interest rate.
ρ = ∂C/∂r
Where:
r is the risk-free interest rate.
For call options, Rho is positive because higher interest rates reduce the present value of the strike price, making the call option more valuable.
For put options, Rho is negative because higher interest rates decrease the value of the put option.


Usages
Delta: Used to gauge the directional risk of an option. For example, a Delta of 0.5 means the option will move $0.50 for every $1.00 move in the underlying asset.
Gamma: Important for understanding how Delta changes as the underlying asset price changes. High Gamma means Delta is highly sensitive to price movements.
Theta: Crucial for options sellers, as it represents how much value the option loses as it approaches expiration.
Vega: Used to assess the impact of volatility changes on the option's price. Options traders might use Vega to trade volatility rather than the direction of the underlying asset.
Rho: Less commonly traded directly, but it is important for understanding the impact of interest rate changes on option prices.

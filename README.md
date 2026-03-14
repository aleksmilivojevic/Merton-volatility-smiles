We simulate price paths using the Merton jump-diffusion model, which is a modification of geometric Brownian motion with added lognormally distributed "jumps" which occur according to a Poisson process.

We Monte-Carlo-simulate Eurocall and Europut prices, and visualize the implied volatility surface (taking in the strike and time to maturity and outputting the parameter $\sigma$ that would be appropriate if the instrument were modelled using ordinary geometric Brownian motion.)

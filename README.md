java c
Assignment 1, MgtF402 Investment Analysis (due October 7, 2024)
Part I: HBS case study #5-205-040: Deutsche Bank: Discussing the Equity Risk Premium
The equity risk premium has been described as the single most important variable in finance. It is also very difficult to estimate precisely. This case describes a variety of approaches to determine the equity risk premium. You will get experience with these by using real data from a variety of sources. The “Data” sheet in the excel file Assignment 1_MF402_2024.xlsx, available from the Assignment 1 folder on Canvas, has monthly returns on stocks, bonds and T-bills going back to January 1970. The spreadsheet has columns with the date (column A), returns on a value-weighted stock portfolio (column B), returns on 10-year Treasury bonds (column E), and the 3-month T-bill rate (column G). Returns are reported as fractions per month so 0.05 means five percent. We also show total return indexes (including dividends and coupons) on US stocks, 10-year Treasury bonds and 3-month T-bills in columns C, F and H). These track how $100 grows over time on a cumulative basis, starting from January 1970.
1. Using these data, estimate the average excess return on stocks (over the T-bill rate) over the full sample period going back to 1970. You can do this by subtracting the T-bill return column (G) from the stock return column (B). Annualize the monthly mean return figures by multiplying by 12. How precise is your estimate? [Hint: run a regression of excess returns (y-variable) on a constant (one) to get standard errors on the mean excess return (equity risk premium) and construct a 95% confidence interval.]
2. How stable is the historical estimate of the equity risk premium over time? [Hint: compute mean returns over a 10-year rolling window (an average over the previous 120 months) and plot this over time.] Comment on your findings.
3. Use the Gordon growth model to estimate the expected risk premium on stocks. Data on the current dividend yield is provided at the bottom of column D. (For explanations of this approach, see Section 18.3 in BKM.) For an estimate of the growth rate of the US economy, see the Survey of Professional Forecasters’ web site at the Federal Reserve Bank of Philadelphia:
and click on the third quarter 2024 release. Choose the annual 2027 growth rate.
For an estimate of the real bond yield extracted from 10-year Treasury Inflation-Protected Securities (TIPS), see here.
4. What estimate of the equity risk premium would you get if you used the ‘novel’ approach on slide 9 of the case study based on the current earnings yield and the real bond yield? The current P/E ratio for the Standard  Poor’s 500 index is around 29.7 – the E/P ratio is its inverse (3.4%).
5. Walmart’s P/E ratio is currently 41.8 while Apple’s P/E ratio is 34.5. Explain why Walmart’s P/E ratio is higher than that of Apple. In doing so, also look at the historical growth rates for the two companies as well as expected earnings growth
Part II: Calculating Risk measures for stocks and bonds
1. Using the historical data on monthly stock returns and 10-year Treasury bonds from the Data sheet of the Assignment_1_MF402_2024.xlsx file, for each of thes代 写Assignment 1, MgtF402 Investment AnalysisPython
代做程序编程语言e assets estimate the following
a. Sharpe ratio (the monthly mean excess return divided by the monthly standard deviation. Multiply by the square root of 12 to annualize).
b. The 3% Value at risk (sort the returns data, then report the third percentile of the empirical return distribution).
c. Expected shortfall at α = 3%. (average of returns below the 3% Value at Risk cutoff).
d. Skew.
e. Kurtosis.
f. Maximum drawdown over the sample (please report as a percent).
g. Are monthly stock and bond returns normally distributed? Provide a plot and test this formally. 
2. For an investor with a coefficient of risk aversion A = 5, compute the optimal allocation to cash (T-bills), stocks and 10-year T-bonds. Your allocation should use the 3-month T-bill rate at the end of the sample as the risk-free rate and sample estimates of the mean, variance and covariance for 10-year Treasury bonds and stocks. [hint: to do this, you can use Lecture 1 slides 73-76.]
3. The total return indexes in columns C, F and H show the cumulative returns (including dividends or coupons) on US stocks, 10-year Treasury bonds and 3-month T-bills. You can use these to compute the total holding period return over any h-month period as (Indext+h-Indext)/Indext. Use this to answer the following questions:
a. How often (as a percentage of time) did stocks underperform. 10-year bonds on a monthly basis (h=1)?
b. How often did this happen at the 1-year (h=12), 5-year (h=60) and 10-year horizons (h=120)?
c. Are bonds safer than stocks? How does your answer depend on the investment horizon?
Part III: Inflation hedge
After being quite low for almost 40 years, inflation roared back in 2021-23 and many investors are looking for an asset that can hedge against future inflationary shocks, i.e., an asset whose returns are also higher when the inflation rate is high, so that its real (inflation-adjusted) returns do not become large and negative. You are asked to consider whether the following assets are a good inflation hedge:
a. US stocks (column C)
b. 3-month T-bills (column H)
c. Gold (column O)
d. Bitcoin (column L)
For each case, report the correlation between percentage changes in the inflation index (column J) over a 3-, 12-, and 24-month horizon and the simultaneous (same-months) percentage changes to the US stock Index, Treasury bill index, Gold index, or Bitcoin index, i.e., Corr(Δlog(Inflindext+h/Inflindext), Δlog(Assetindext+h/Assetindext)). The higher the correlation, the better the asset is at hedging inflation at a horizon (holding period) of h months.
Next, use the Economic Tracking method of Owen Lamont to estimate the weights on a multivariate inflation hedging strategy comprising Gold, the 10-year and 3-month bond returns and the 12 industry portfolios in the excel file. The approach is described in the note on Canvas and you can simply use equation (8) in that note. Again, consider separately the 3-, 12- and 24-month horizons.
i. Summarize your findings on which assets can significantly help hedge inflation.
j. How effective is your inflation hedge portfolio, i.e., can it significantly reduce inflation exposure?



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

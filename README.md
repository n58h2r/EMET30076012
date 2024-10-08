java c
Business and Economic Forecasting EMET3007/6012
Assignment 2
Problem 1                                                            9=2+3+2+2 points
In this exercise we will consider four different specifications for forecasting monthly Australian total employed persons. The dataset (available on Wattle) AUSEmploy2022.csv contains three columns; the first column contains the date; the second contains the number of employed persons for that month (FRED data series LFEMTTTTAUM647N), and the third contains Australian GDP for that month. The data runs from January 1995 to January 2022.
Let Mi be a dummy variable that denotes the i’th month of the year. Let Di be a dummy variable which denotes the i’th quarter of the year. The four specifications we consider are

where Eet = 0 for all t.
a) For each specification, describe this specification in words.
b) For each specification, estimate the values of the parameters, and compute the MSE, AIC, and BIC. If you make any changes to the csv file, please describe the changes you make. As always, you must include your code.
c) For each specification, compute the MSFE for the 1-step and 5-step ahead forecasts, with the out-of-sample forecasting exercise beginning at T0 = 50.
d) For each specification, plot the out-of-sample forecasts and comment on the results.
Problem 2                                                            6 points
Consider the following AR(1) process with drift:
yt = µ + ρyt−1 + εt,
where the errors also follow an AR(1) process:
εt = φεt−1 + ut,
for t = 1, . . . , T, ε0 = 0, and ut are iid N(0, σ2). Suppose φ is known. Derive the log likelihood function given the observations y 代 写EMET3007/6012 Business and Economic Forecasting Assignment 2R
代做程序编程语言= (y1, . . . , yT)0 and the initial y0. Find the maximum likelihood estimators for µ, ρ, and σ2.
Problem 3                                                             16=3+3+4+6 points
The file USCPI.csv contains U.S. inflation rate (computed from consumer price index) from 1947Q2 to 2011Q2.
(a) Fix φ = 0.3. Use the data to fit the AR(1) model in Question 2. Obtain the maximum likelihood estimates for µ, ρ, and σ2.
(b) Now, we estimate φ instead of fixing it at 0.3. Obtain the maximum like-lihood estimates for φ, µ, ρ, and σ2.
(c) Instead of AR(1) errors, consider the following AR(1) model with MA(1) errors:
yt = µ + ρyt−1 + εt,
εt = ut + ψut−1,
for t = 1, . . . , T, where u0 = 0 and ut are iid N(0, σ2) for t ≥ 1. Derive the log likelihood function given the observations y = (y1, . . . , yT)0 and the initial y0.
(d) Use the inflation data to obtain the maximum likelihood estimates for ψ, µ, ρ, and σ2. Which model fits the data better? AR(1) or MA(1) errors?
Problem 4                                                             6 points
Consider the ARX(1) model
yt = µ + at + ρyt−1 + e t
where the errors follow an AR(2) process
et = φ1et−1 + φ2et−2 + ut, u ∼ N (0, σ2I)
for t = 1, . . . , T and e−1 = e0 = 0. Suppose φ1, φ2 are known. Find (analyti-cally) the maximum likelihood estimators for µ, a, ρ, and σ2.
[Hint: First write y and e in vector/matrix form. You may wish to use different looking forms for each. Find the distribution of e and y. Then apply some appropriate calculus. You may want to let H = I − φ1L − φ2L2, where I is the T × T identity matrix, and L is the lag matrix.]





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

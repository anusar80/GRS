# GRS
This function computes the Gibbons, Ross, and Shanken (1989) test statistic. The null hypothesis of the GRS test is that all the intercepts in the time-series regressions vanish jointly. The function returns the F-statistic and its associated p-value. Call as follows:

F, pVal = GRS(alpha, resids, mu)

where alpha is an Nx1 vector of intercepts of the time-series regressions, resids is a TxN matrix of residuals of the same, and mu is a TxL matrix of factor returns. So we are assuming we have N assets, T factors, and T time points of observed returns. 

Gibbons, Michael R., Stephen A. Ross, and Jay Shanken. "A test of the efficiency of a given portfolio." Econometrica: Journal of the Econometric Society (1989): 1121-1152.


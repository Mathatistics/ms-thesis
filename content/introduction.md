# Introduction

Apart from having distinct role in money market, exchange rate has influence in almost all the sectors of economics and finance. Understanding its dynamics enables multinational companies to make decision on their investment and assist bureaucrats to update the monetary and fiscal policies. Different models are used to understand the dynamics of exchange rate, however the use of latent variable in the models is unconventional. Multicollinearity which is also a common problem in economic researches, models based on principal components (latent variables) such as Principal Component Regression(PCR) and Partial Least Square(PLS) regression can resolve the problem. Although autocorrelation is a major problem in time-series, inclusion of the past values of dependent variable in the model can solve the problem in many situations. In this dissertation the exchange rate of Norwegian Krone vs Euro is predicted from the classical linear regression models, its subsets derived from various criteria, PCR and PLS models. The models are compared on the basis of their performance. Under proper model specification and wise selection of required components, Principal Component Regression and Partial Least Square regression can forecast better than the linear models.

Trading has started from the very beginning of human civilization. People used to trade with goods at the time but with advancement of development people started using gold, silver and finally money. The process is not restricted within a country. Some countries are powerful and some are not so as their currencies. Currency of another country becomes essential to buy things from that country. Here comes the role of exchange rate. Buying powerful currencies requires large sum of weak currencies. 

Any international trade is conducted through more than one currencies. Participants in the international trade require to exchange their currency which is performed by foreign exchange market. &#8220;The foreign exchange market (ForEx) is the mechanism that brings together buyers and sellers of different currencies&#8221; (appleyard2014international).

As any other commodity, exchange rate is also determined from its demand and supply in money market. All those economic activities that exist between countries create demand and supply of the currencies which consequently determine the exchange rate. The economic activities between countries are recorded as balance of payment account. Thus the balance of payment account captures all the demand and supply of foreign currency (fang1991forecasting). When the domestic demand for foreign currency exceeds the foreign demand of domestic currency i.e. a deficit in the balance of payment, the domestic currency depreciate (sur2005).

Foreign currencies are involved in various activities such as, a) imports and exports of goods and services, b) interest and dividends payed to foreign investment in domestic market, c) interest and dividends earned from investments made on foreign market, d) all the currencies that enter into and leave from a country as income and expenditure.

Three factors affecting exchange rate are considered in this thesis. Primarily, total monthly imports and exports of goods are considered. Ships, oil platform, chemicals and food stuffs are major imports of Norway. Petroleum products, machinery, equipment, chemicals and fishes are the major exports. Since the economy of Norway highly depend on petroleum products, apart from imports and exports, the second component considered is the spot oil price. Third factor is the financial variables such as interest rate and consumer price index are considered. In interest rate &#8211; a) key interest rate of Norway, b) Loan interest rate c) key interest rate of euro area are taken into account as factors affecting interest rate.

## Methods opted for analysis ##

Univariate time series analysis is very common in Econometric where Autoregressive (AR), Moving Average (MA) and Autoregressive integrated Moving average (ARIMA) are used. However, dealing a time series data with many predictor variables using latent variables and principal components methods is unconventional. This thesis aims to analysis a time series with financial and commodity data, as predictor, using statistical regression methods such as &#8211; Multiple Linear Regression, Ridge Regression, Principal Component Regression (PCR) and Partial Least Square (PLS) Regression. Apart from these, a subset models which selected from the Multiparty Linear Regression using various criteria are also used. An application of PCR and PLS on time series data makes this thesis distinct.

## Sources of data ##

Data related to balance of payment such as import, export and trade balance used here are obtained from [Statistics Norway][1]. Consumer price index is also obtained from the same source. Interest rate variable related to Norway are obtained from [Norges&#8217; Bank][2] and the key interest rate for euro zone is obtained from [Euro Bank][3] while the oil spot price is obtained from [US Energy information system][4]. The average monthly spot price for Brent oil was on Dollar per Barrel unit which was converted into NOK using NOK per USD exchange rate for that month.

## Objective of thesis ##

There are three main objective of this thesis-

  1. To analyze the relationship of foreign exchange rate with the financial (price, indices and exchange rate) and commodity (imports, exports and trade balance) information
  2. Prediction of out-of-sample observations (Exchange Rate) using various models
  3. Comparison of the Models considered on the basis of goodness of their fit and their predictive ability

 [1]: http://ssb.no
 [2]: http://www.norges-bank.no/en/Statistics/Interest-rates/Key-policy-rate-monthly/
 [3]: http://ec.europa.eu/eurostat/web/interest-rates/database
 [4]: http://www.eia.gov/dnav/pet/pet_pri_spt_s1_m.htm

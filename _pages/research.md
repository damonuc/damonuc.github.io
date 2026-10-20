---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Job Market Paper

### Forecasting Firm-Level Tail Risk with Structured Mixture Density Networks

[Read the paper (PDF)]({{ '/files/Jianbin_Chen_JMP.pdf' | relative_url }}) · October 2026

**Abstract.** This paper develops structured mixture density networks to forecast U.S. stock return distributions and identify exposure to market declines. Macroeconomic information determines the probabilities of a future market state shared by all firms, while firm characteristics determine returns within each state. The joint model combines a common market environment with heterogeneous firm outcomes. Across 216 out-of-sample formation months from 2007 to 2024, three structured specifications improve density and tail forecast scores relative to neural Normal and unrestricted mixture benchmarks. The forecasts also provide an exact decomposition of expected shortfall (ES) into component contributions. After controlling for total ES, historical exposures, and predicted mean and volatility, the low-mean component contribution distinguishes stocks with different crash risks in bad markets. The lowest and highest residual contribution deciles differ in crash rates by 6.4--7.1 percentage points using 5% ES and 6.2--7.6 points using 10% ES, with small differences in other months. These signals are formed before returns are observed. Forecast gains and positive bad-market crash-rate gaps persist across two additional random seeds and fixed-epoch training. The findings show that both the size and composition of predicted tail losses help identify stocks that are vulnerable during market declines.

<!-- [Code on GitHub](https://github.com/damonuc/PricingTailRisk_MDN) -->

## Working Papers

### From Startups to Stocks: Text-Based Matching and Public Equity Returns

**Abstract.** This paper examines whether business descriptions of early-stage startups contain information relevant to public equity returns. I develop a text-based framework that links Y Combinator startups to publicly traded U.S. firms with similar products and business models. The framework combines sentence embeddings, cross-encoder re-ranking, and large language model evaluations to identify public-market counterparts to private startups. Using these matches, I construct tradable portfolios following each accelerator cohort and evaluate their performance through five-year buy-and-hold returns and calendar-time factor regressions. Across matching methods, the portfolios outperform the S&P 500 over five-year holding periods, with statistical inference accounting for overlapping investment horizons. Calendar-time portfolios also exhibit positive risk-adjusted returns, with several specifications producing statistically significant alphas under the Fama–French five-factor model. The large language model specification delivers the highest estimated five-factor alpha, although performance rankings vary across evaluation methods. These findings suggest that startup business descriptions provide a useful signal for identifying public firms exposed to emerging business models and technologies. The paper contributes a scalable approach to connecting private-market innovation with public-market investment opportunities.

<!-- [Code on GitHub](https://github.com/damonuc/YC_Startup) -->

### Financial Statements and the Predictability of Earnings Changes: Evidence from Neural Networks

**Abstract.** This paper examines how much information about one-year-ahead earnings changes can be extracted from widely available financial statement line items and whether neural-network architecture affects the out-of-sample usefulness of that information. Using nearly 229,000 firm-year observations for North American public firms, I construct 98 features from the balance sheet, income statement, and statement of cash flows. Models are estimated using data from 1990–2016 and evaluated out of sample from 2017 onward. Deeper feedforward networks generally improve accuracy and AUC relative to shallower networks, although the gains level off at five to six layers. Standard normalization and dropout do not consistently improve performance. An ensemble combining networks of different depths attains approximately 65% accuracy and performs comparably to random forests and XGBoost. Predictive performance varies across industries and declines as the test period moves farther from the training sample, indicating economically important distribution shifts. Portfolio tests suggest that predicted earnings reversals contain economic information, but risk-adjusted performance is sensitive to portfolio construction. Overall, the findings document both the promise and the limits of using neural networks to extract forward-looking signals from standardized financial statements.

<!-- [Code on GitHub](https://github.com/damonuc/Predict_NI) -->

## Publication

**CEO Turnover and Stock Price Reactions: Evidence from China** (with Ke Peng). *South China Finance*, 2014(07), pp. 60–68.

This paper examines short-term stock price reactions to CEO turnover in Chinese listed companies using event study methodology and multivariate regression. The results provide evidence of information leakage and identify firm performance, dividend payments, and information asymmetry as factors associated with abnormal returns.

## Presentations

- Econometrics Seminar, University of California, Riverside — March 2026.

## Referee Service

- *Journal of Business Cycle Research*.

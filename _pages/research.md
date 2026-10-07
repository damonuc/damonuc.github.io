---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Job Market Paper

### Firm-Level Tail Risk and Stock Returns: A Structured Mixture Density Approach

**Abstract.** This paper examines whether predicted firm-level tail risk is associated with subsequent stock returns. I develop a structured mixture density network that forecasts individual stocks’ one-month-ahead return distributions. Macroeconomic variables determine component probabilities shared across firms, while firm characteristics determine component means and scales. This structure allows expected shortfall to be decomposed into component-specific tail probabilities and conditional loss severity. In an out-of-sample evaluation covering 2007–2024, the structured model outperforms historical, linear quantile, and unrestricted neural benchmarks across the reported forecast-loss measures. Stocks with more severe predicted tail losses subsequently earn lower returns, particularly in equal-weighted portfolios. The equal-weighted spread between stocks with less and more severe predicted losses has a five-factor-plus-momentum alpha of 1.06% per month. Component-level tests further indicate that this return relation varies with the model-implied adverse-state probability. Rank-standardized predictors preserve the principal forecasting and equal-weighted portfolio findings. Overall, the evidence links predicted tail losses to persistent firm distress rather than a simple positive premium for greater tail risk.

<!-- [Code on GitHub](https://github.com/damonuc/PricingTailRisk_MDN) -->

## Working Papers

### From Startups to Stocks: Text-Based Matching and Public Equity Returns

**Abstract.** This paper examines whether business descriptions of early-stage startups contain information relevant to public equity returns. I develop a text-based framework that links Y Combinator startups to publicly traded U.S. firms with similar products and business models. The framework combines sentence embeddings, cross-encoder re-ranking, and large language model evaluations to identify public-market counterparts to private startups. Using these matches, I construct tradable portfolios following each accelerator cohort and evaluate their performance through five-year buy-and-hold returns and calendar-time factor regressions. Across matching methods, the portfolios outperform the S&P 500 over five-year holding periods, with statistical inference accounting for overlapping investment horizons. Calendar-time portfolios also exhibit positive risk-adjusted returns, with several specifications producing statistically significant alphas under the Fama–French five-factor model. The large language model specification delivers the highest estimated five-factor alpha, although performance rankings vary across evaluation methods. These findings suggest that startup business descriptions provide a useful signal for identifying public firms exposed to emerging business models and technologies. The paper contributes a scalable approach to connecting private-market innovation with public-market investment opportunities.

<!-- [Code on GitHub](https://github.com/damonuc/YC_Startup) -->

### Financial Statements and the Predictability of Earnings Changes: Evidence from Neural Networks

**Abstract.** This paper examines how much information about one-year-ahead earnings changes can be extracted from widely available financial statement line items and whether neural-network architecture affects the out-of-sample usefulness of that information. Using nearly 229,000 firm-year observations for North American public firms, I construct 98 features from the balance sheet, income statement, and statement of cash flows. Models are estimated using data from 1990–2016 and evaluated out of sample from 2017 onward. Deeper feedforward networks generally improve accuracy and AUC relative to shallower networks, although the gains level off at five to six layers. Standard normalization and dropout do not consistently improve performance. An ensemble combining networks of different depths attains approximately 65% accuracy and performs comparably to random forests and XGBoost. Predictive performance varies across industries and declines as the test period moves farther from the training sample, indicating economically important distribution shifts. Portfolio tests suggest that predicted earnings reversals contain economic information, but risk-adjusted performance is sensitive to portfolio construction. Overall, the findings document both the promise and the limits of using neural networks to extract forward-looking signals from standardized financial statements.

<!-- [Code on GitHub](https://github.com/damonuc/Predict_NI) -->

## Publication

**CEO Turnover and Stock Price Reactions: Evidence from China.** *South China Finance*, 2014(07), pp. 60–68.

# IC_MF_Market_Microstructure_CW
This repository stores the Coursework for Market Microstructure module for Imperial Math Finance Program.

## Abstract

This paper replicates the analysis of microstructural hedging errors arising from discrete rebalancing and bid-ask bounce in realistic markets. Using an uncertainty zone framework, we evaluate hedging errors across different strategies and demonstrate that an optimal rebalancing approach can asymptotically mitigate microstructure noise. Numerical simulations confirm these findings and highlight the impact of key parameters. Additionally, we extend our analysis to a stochastic volatility model and asymmetric $\eta$, demonstrating its adaptability. Finally, we discuss the limitations of the framework and suggest potential improvements to better incorporate market microstructure effects.

## Contributor

Zhenyi Chen   (CID: 06011402)\\
Yi Qu (CID:06001389)\\
Chengdong Song (CID: 02030540)

## Structure

```hedging_error_GBM_params.ipynb```
This notebook analyzes the influence of parameters of hedging errors under the Geometric Brownian Motion (GBM) model. It examines how parameter choices influence hedging performance and explores error distributions.

```hedging_error_SABR_Bartlett_Delta.ipynb```
Implements SABR model hedging using Bartlett Delta. It investigates how the volatility dynamics impact hedging efficiency and error behavior.

```hedging_error_SABR_Bartlett_Delta_asym_eta.ipynb```
Extends the SABR Bartlett Delta model by introducing asymmetric bid-ask spreads, where the upper and lower thresholds differ, reflecting real-world market imbalances.

```hedging_error_SABR_Delta_NEW.ipynb```
An extention to the Hedging error of SABR model using classic Delta.

```hedging_error_SABR_Delta_NEW_asym_eta.ipynb```
Further extends the SABR model by incorporating asymmetric bid-ask dynamics into the updated hedging framework.

```hedging_error_vision3.ipynb```
Implement the Hedging Error Analysis in the original paper, reproducing a similar result.

```hedging_error_vision3_asym_eta.ipynb```
A variation of ```hedging_error_vision3.ipynb``` incorporating asymmetric bid-ask spreads, allowing for a more realistic assessment of market liquidity effects on hedging performance.

# IC_MF_Market_Microstructure_CW
This repository stores the Coursework for Market Microstructure module for Imperial Math Finance Program.

## Abstract

This paper replicates the analysis of microstructural hedging errors arising from discrete rebalancing and bid-ask bounce in realistic markets. Using an uncertainty zone framework, we evaluate hedging errors across different strategies and demonstrate that an optimal rebalancing approach can asymptotically mitigate microstructure noise. Numerical simulations confirm these findings and highlight the impact of key parameters. Additionally, we extend our analysis to a stochastic volatility model and asymmetric $\eta$, demonstrating its adaptability. Finally, we discuss the limitations of the framework and suggest potential improvements to better incorporate market microstructure effects.

## Contributor

Zhenyi Chen   (CID: 06011402)
Yi Qu (CID:06001389)
Chengdong Song (CID: 02030540)

## Structure

IC_MF_Market_Microstructure_CW/
│── early_version/                      # Previous versions of the project, just ignore them
│── README.md                           # Project documentation
│── hedging_error_GBM_params.ipynb      # Parameter Analysis for Hedging error (under GBM)
│── hedging_error_SABR_Bartlett_Delta.ipynb      # Hedging error of SABR model with Bartlett Delta
│── hedging_error_SABR_Bartlett_Delta_asym_eta.ipynb  # Asymmetric bid-ask variation for SABR Bartlett Delta Delta
│── hedging_error_SABR_Delta_NEW.ipynb  # Hedging error for SABR model Using Classic Delta
│── hedging_error_SABR_Delta_NEW_asym_eta.ipynb  # Asymmetric eta in SABR model 
│── hedging_error_vision3.ipynb         # Replicated hedging error analysis
│── hedging_error_vision3_asym_eta.ipynb  #  hedging error analysis with asymmetric eta

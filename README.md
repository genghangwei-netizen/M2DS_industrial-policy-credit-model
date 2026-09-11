# M2DS Industrial Policy Credit Model

This repository contains the experimental code developed for my Master 2 Data Science internship report:

**Firm-Level Response under Industrial Policy Exposure:  
A Data-Science Framework for Banking Credit Decision Support**

The project investigates how industrial-policy information, supply-chain structure and firm-level financial indicators can be integrated into a quantitative decision-support framework for banking applications.

## Notebooks

1. `01_policy_exposure.ipynb`  
   Policy-intensity construction, industry-level exposure measurement and panel analysis.

2. `02_supply_chain_network.ipynb`  
   Supply-chain network analysis, centrality measures, chain-leader identification and robustness to missing links.

3. `03_firm_level_prediction.ipynb`  
   Temporal supervised learning, policy-feature ablation, model comparison, permutation importance and exploratory clustering.

4. `04_robustness_credit_review.ipynb`  
   End-to-end robustness analysis under policy, network and financial-data uncertainty, followed by an illustrative credit-review prioritisation framework.

## Data

Policy records and industry-level R&D indicators are based on public information.

The firm-level financial panel and supplier-customer network used in the experiments are synthetic and are intended for methodological validation rather than for estimating real-world bank portfolio performance.

## Disclaimer

This project is a research and decision-support framework. It is not an automated credit-approval system or a production credit-risk model.

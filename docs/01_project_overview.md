# Step 0: Project Overview

## Title
**Probabilistic Machine Learning for Modeling Uncertainty and Cost in Vision-Based Inspection Systems**

---

## Problem Statement
Automated vision inspection systems are widely used on the shop floor to measure part dimensions and ensure quality.  
However, their outputs are not perfectly reliable:

- **Aleatoric uncertainty** arises from measurement noise, lighting variation, and surface properties.  
- **Epistemic uncertainty** arises from limited calibration, operator differences, and model assumptions.  

These uncertainties lead to **false rejects** (good parts scrapped) and **false accepts** (bad parts shipped).  
Both outcomes create significant operational costs, either through wasted material/labor or warranty claims and recalls.

---

## Research Objective
This project aims to:

1. **Simulate and model measurement uncertainty** (aleatoric + epistemic).  
2. **Apply machine learning methods** to quantify uncertainty in inspection decisions.  
3. **Link uncertainty to cost impact** by modeling probabilities of false rejects and false accepts.  
4. **Compare classical statistical approaches vs ML-based approaches** for decision-making under uncertainty.  

---

## Why It Matters
- **Industry impact:** Helps manufacturers quantify the financial consequences of inspection errors and justify investments in better inspection systems.  
- **Academic contribution:** Bridges stochastic uncertainty modeling, machine learning, and practical manufacturing decision-making.  
- **Reproducibility:** Uses synthetic/public datasets to ensure results can be replicated without relying on confidential factory data.  

---

## Planned Workflow
1. **Dataset Creation** → Generate synthetic measurement data with controlled noise (aleatoric) and operator/machine bias (epistemic).  
2. **Baseline Analysis** → Apply classical quality methods (Gauge R&R, confidence intervals) to establish a benchmark.  
3. **ML Modeling** → Train logistic regression, ensembles, and Bayesian methods to classify parts and estimate uncertainty.  
4. **Uncertainty Quantification** → Distinguish aleatoric vs epistemic contributions to prediction uncertainty.  
5. **Decision Modeling** → Define probability thresholds for accept/reject/reinspect decisions.  
6. **Cost Simulation** → Translate inspection outcomes into expected cost (scrap, rework, false accept).  
7. **Sensitivity Analysis** → Explore how varying noise, bias, costs, and thresholds affect outcomes.  
8. **Results & Discussion** → Compare classical vs ML approaches and provide actionable insights for manufacturing.  

---

## Status
🚧 Project initiation (Step 0). Next: Dataset generation and baseline analysis.

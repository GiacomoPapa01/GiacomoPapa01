# Giacomo Papa

**Quantitative Analyst** — Mathematical Engineering · FX Derivatives


I hold an MSc in Mathematical Engineering with a specialization in Quantitative Finance from Politecnico di Milano, and professional experience at **Murex** (Paris), where I worked on the pricing and lifecycle management of FX derivatives, cross-currency swaps, non-deliverable forwards, interest rate swaps, on the MX.3 platform.

My background spans the full spectrum from rigorous mathematical modeling to hands-on implementation. I am equally comfortable deriving a pricing model from first principles, building a numerical simulation, or integrating a quantitative framework into a production system.

I have a strong inclination toward experimentation particularly at the intersection of classical quantitative finance and modern machine learning. My personal projects reflect a consistent interest in pushing standard methodologies further: applying Hidden Markov Models for regime detection, exploring Kalman filtering for dynamic factor estimation, and incorporating ensemble methods and shrinkage estimators where classical approaches fall short. I actively explore deep learning architectures in the context of financial time series, signal generation, and feature extraction.

---

## Projects

### Blood Cell Classification (CNN)
8-class image classification of blood cell types — Basophil, Eosinophil, Erythroblast, Immature Granulocytes, Lymphocyte, Monocyte, Neutrophil, and Platelet — developed as part of the Artificial Neural Networks and Deep Learning course at Politecnico di Milano. The architecture is based on **MobileNetV3Large** fine-tuned via transfer learning on ImageNet weights, with a custom classification head. The training pipeline includes aggressive data augmentation (random rotation, translation, CutMix), class balancing via targeted oversampling for the most misclassified categories, and a two-phase fine-tuning schedule with learning rate reduction. The final model achieved an accuracy and F1 score of **98.5%** on the held-out test set, with the team ranking in the **top 8 out of over 300** participants on the course leaderboard.

### Martian Terrain Segmentation (U-Net)
Pixel-level semantic segmentation of grayscale Mars surface imagery into five terrain classes — Background, Soil, Bedrock, Sand, and Big Rock — developed as part of the same deep learning course. The architecture is a custom **U-Net** with dilated convolutions in the encoder path, an **ASPP (Atrous Spatial Pyramid Pooling)** bottleneck for multi-scale context aggregation, and skip connections throughout the decoder. To address the extreme class imbalance (particularly the rarity of Big Rock regions), the model was trained with **Focal Categorical Crossentropy loss** with manually tuned per-class alpha weights. The training procedure involved label correction of mislabeled samples, custom color-augmented datasets for underrepresented classes, and a scheduled learning rate reduction strategy. The best model achieved a **Mean Intersection over Union (mIoU) of 78.03%** on the validation set.

### Systematic Equity System (Python)
A modular, research-grade pipeline for systematic equity investing built across three interconnected components:
- **Walk-forward optimizer** — portfolio scoring via a composite metric (Sharpe, Calmar, Win Rate, Profit Factor) with HMM-based market regime classification and cached pre-fitting for computational efficiency
- **Daily decision engine** — Kelly-criterion position sizing integrated with a fundamental score multiplier
- **Fundamental analyzer** — multi-factor scoring across corporate health, valuation, growth, and macro regime, structured over five discrete states

### Black-Box Index Replication
Dynamic replication of an undisclosed benchmark using a **Kalman Filter** initialized with Ridge regression coefficients, ensembled with a **James-Stein shrinkage** estimator. The system incorporates a pairs trading overlay and was developed as part of a FinTech course at Politecnico di Milano.

### Asset Allocation Study
Systematic comparison of **16 portfolio construction methodologies**: Markowitz mean-variance, resampling, Black-Litterman, maximum diversification, maximum entropy, PCA-based dimensionality reduction, and VaR-adjusted approaches — evaluated across a consistent set of risk-adjusted return metrics.



---

## Background

- MSc Mathematical Engineering — Quantitative Finance · Politecnico di Milano  
- Product & Expertise Specialist · Murex, Paris — FX Derivatives, XCS, IRS, CDS on MX.3  
- Based in Milan · open to roles in Milan, Paris, Luxembourg

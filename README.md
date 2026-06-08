Project Overview

This repository explores weather-driven bike-sharing demand in Seoul, South Korea using interpretable multivariate statistical methods. The workflow integrates hourly rental counts with weather conditions to uncover underlying weather patterns and use them for demand prediction.

Methods

PCA (Principal Component Analysis): compresses correlated weather variables into a smaller set of orthogonal components (3 PCs explain ~69.2% variance).
FA (Factor Analysis): extracts interpretable latent factors (3 factors explain ~56.8% common variance).
LDA (Linear Discriminant Analysis): classifies demand into Low/Medium/High using PCA/FA-derived features.

Results

LDA achieves ~70.73% accuracy in demand classification.
Demand increases under warm, dry, clear conditions (especially during peak commute hours) and decreases under cold/rainy conditions (notably off-peak).

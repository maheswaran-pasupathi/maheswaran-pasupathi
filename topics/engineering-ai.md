# Engineering AI

This page is about how I am applying data-driven methods to CFD, thermal and engineering-simulation problems while keeping physical interpretation and validation central.

## Topics I cover

- Engineering feature formulation
- Regression and classification
- Surrogate modelling
- Explainable ML
- POD/PCA and reduced representations
- Optimization on surrogate models
- Scientific ML / PINN / neural-operator exploration
- RAG and engineering knowledge workflows

## How I approach these problems

The first question is not which algorithm to use. It is what the engineering problem actually is, what the data physically represents, which variables should be features and targets, and what evidence would make a prediction useful.

I prefer a simple, interpretable baseline before increasing model complexity. Statistical accuracy is not enough by itself; extrapolation, uncertainty, physical consistency and engineering usefulness matter.

## Public portfolio

### [AI for Thermal & Fluid Engineering](https://github.com/maheswaran-pasupathi/ai-thermal-fluids)

Current public projects include:

- In-cylinder PIV flow reconstruction using POD/PCA and regression
- Spray and combustion ML with tree models and SHAP interpretation
- Thermal surrogate modelling and bounded cooling optimization
- Planned extensions into vehicle aerodynamics, thermal-field prediction and Scientific ML

All public projects use public/research data rather than proprietary employer data.

## I am adding next

Deeper validation, uncertainty/extrapolation checks, additional thermal and vehicle datasets, and more explicit comparison between conventional physics models and data-driven acceleration methods.

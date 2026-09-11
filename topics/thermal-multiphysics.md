# Thermal & Multiphysics

This page is my compact technical map for thermal-fluid and multiphysics work. It is intended to explain the kinds of engineering questions I work on, the modelling choices I care about, and the public examples I can share.

## Topics I cover

- Conjugate heat transfer (CHT)
- Coolant and internal-flow distribution
- Temperature and hotspot prediction
- Electro-thermal / Joule-heating workflows
- Thermal resistance and heat-flow interpretation
- Steady and transient thermal analysis
- Simulation-to-test correlation
- DOE and design sensitivity

## How I approach these problems

I usually start with the heat-flow path and the engineering decision rather than with the solver. That means checking energy balance, dominant resistances, boundary-condition sensitivity and expected temperature scales before increasing model fidelity.

For coupled problems, I separate what is directly solved from what is imposed or transferred between models, and I treat validation and uncertainty as part of the modelling workflow rather than as an end-of-project check.

## Selected evidence

- Electro-thermal busbar analysis combining Joule heating and CHT, with peak-temperature correlation against thermocouple measurements.
- Engine/coolant thermal-fluid and CHT studies used to support design recommendations.
- Automation of simulation execution, KPI extraction and post-processing for repeatable engineering workflows.

## Public work

- [AI for Thermal & Fluid Engineering](https://github.com/maheswaran-pasupathi/ai-thermal-fluids) — public projects covering thermal surrogates, cooling optimization and physics-aware ML.

## I am adding next

Sanitized technical notes and small reproducible examples that explain modelling assumptions, validation logic and engineering interpretation without exposing proprietary data.

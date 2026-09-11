# Simulation Methods & Automation

This page collects the methods I use to make simulation work more repeatable, scalable and decision-focused.

## Topics I cover

- STAR-CCM+ Java automation
- Python workflow automation
- Batch execution and monitoring
- KPI extraction and reporting
- DOE and parametric studies
- Model fidelity and simplification
- 1D–3D coupling
- Surrogate modelling / ROM concepts
- Repeatable simulation-method development

## How I approach these problems

Automation is useful when it removes repetition without hiding the physics. I prefer workflows where the engineer can still inspect assumptions, inputs, convergence, outputs and failure modes.

The same principle applies to model simplification: reduce complexity only when the simplified model still preserves the behaviour needed for the engineering decision.

## Selected evidence

- Python and STAR-CCM+ Java workflows for setup, execution, KPI extraction and reporting.
- Simulation-turnaround reduction of roughly 40–50% in repeat workflows.
- DOE, optimization and surrogate-model approaches used to explore engineering design spaces efficiently.

## Public work

- [AI for Thermal & Fluid Engineering](https://github.com/maheswaran-pasupathi/ai-thermal-fluids) — public examples of surrogate modelling, optimization and physics-aware engineering ML.

## I am adding next

Sanitized automation examples and reusable utilities that demonstrate workflow structure without exposing employer-specific models, geometry or data.

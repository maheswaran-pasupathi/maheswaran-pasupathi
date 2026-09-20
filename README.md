# Maheswaran Pasupathi

### Battery Cooling & Thermal Performance × Vehicle Thermal Management × 1D–3D System Simulation × Automation

I am a senior thermal specialist with **9 years of experience** in automotive and heavy-duty engineering. My primary focus is **battery cooling and thermal performance** and **vehicle thermal management** (cabin HVAC and heat pump, battery and e-powertrain cooling), using **GT-SUITE 1D system models coupled with STAR-CCM+ 3D conjugate heat transfer** and correlating models with test data. Around this I work on battery thermal safety, electro-thermal analysis, Python/Java automation and engineering AI. I work with test, design and quality teams and follow Agile delivery with documented, reviewable results.

My experience spans **Renault Nissan Technology & Business Centre India** and **MAN Truck & Bus India**, including collaboration with engineering teams in Germany and Sweden.

[Professional experience](#professional-experience) · [Open-source projects](#open-source-projects) · [LinkedIn](https://www.linkedin.com/in/srimahes)

## Professional experience

Expand a topic to see the projects, my contribution and the engineering questions behind the work.

<details open>
<summary><strong>Battery cooling & thermal performance</strong> — 1D coolant networks, 3D CHT and thermal propagation</summary>

### Projects and contribution

- **Battery cooling assessment:** evaluated cooling architecture with a 1D coolant network and 3D conjugate heat transfer, covering peak temperature and temperature spread, branch-flow distribution, circuit pressure loss, pump operating point and cold-plate performance.
- **Cooling concepts:** compared pack-level cooling with individual-cell cooling for temperature uniformity, and radiator with chiller operation for shared battery and cabin demand and auxiliary energy.
- **Thermal-runaway and propagation:** worked on coupled 3D–1D propagation assessment, comparing cell-skin temperatures with calorimeter data and reviewing inter-cell heat paths and cooling conditions.
- **Cold-ambient performance:** studied how heating strategy, thermal insulation and recuperation limits affect battery and vehicle performance.
- **Test correlation:** compared predictions with thermocouple, calorimeter and coolant measurements, and used the results to support design suggestions.

**Engineering focus:** temperature and uniformity matter as much as the peak. A calculated coolant flow is a first estimate; branch distribution, the pump operating point and heat rejection decide what the battery actually sees.

**Methods and tools:** GT-SUITE, STAR-CCM+, conjugate heat transfer, 1D–3D coupling, sensitivity studies and test correlation.

[Battery topic notes](https://github.com/maheswaran-pasupathi/maheswaran-pasupathi/blob/main/topics/battery-electrification.md)

</details>

<details>
<summary><strong>Vehicle thermal management & HVAC</strong> — 1D vehicle models, heat-pump modes and test correlation</summary>

### Projects and contribution

- **Full-vehicle 1D thermal models:** worked on modular GT-SUITE vehicle models linking drive cycle, battery, motor, cooling circuits, refrigerant/HVAC circuit and controls, with variant handling and version control for repeatable studies.
- **HVAC and heat-pump modes:** modelled heating and cooling operating modes (waste-heat recovery, electric heater, heat pump, battery-assisted cooling) with pump, valve, compressor and heater control logic, and compared energy demand per mode.
- **Climatic wind-tunnel and drive correlation:** correlated cabin, vent, refrigerant and coolant states with test data and closed gaps through boundary-condition and parameter review.
- **Duty-cycle energy and thermal limits:** assessed auxiliary load, heat rejection and thermal limits over drive cycles, and how they affect vehicle performance.
- **Development process:** validated results, raised improvement suggestions and coordinated with test and design teams against development milestones.

**Engineering focus:** cooling power and electrical input are not the same quantity. Energy comparisons need equal service, and a model is only trusted where it has been correlated.

**Methods and tools:** GT-SUITE, MATLAB/Simulink, Python, 1D–3D coupling, energy balance and test correlation.

</details>

<details>
<summary><strong>System simulation</strong> — GT-SUITE, thermal networks and 1D–3D integration</summary>

### Projects and contribution

- **Model hierarchy:** local 3D CHT to component characterisation, reduced to a 1D representation, then vehicle-level transients and controls, returning limiting cases to 3D when local detail is needed.
- **Interfaces:** defined what is exchanged between 1D and 3D models and checked energy conservation across the interface.
- **Sensitivity and correlation:** assessed boundary conditions and parameter sensitivity, separating calibration from independent validation.
- **Model selection:** helped decide when a system model can answer the question and when local three-dimensional detail is needed.

**Methods and tools:** GT-SUITE, thermal-fluid networks, 1D–3D coupling, sensitivity studies and test correlation.

**Continuing learning:** Modelica for reusable component-based system models.

</details>

<details>
<summary><strong>Busbar & high-voltage connector electro-thermal analysis</strong> — current density, Joule heating and contact optimisation</summary>

### Projects and contribution

- **Coupled electro-thermal modelling:** evaluated electrical heat generation together with solid conduction and surrounding-fluid heat transfer to predict busbar and connector temperature distribution.
- **Current-density and hotspot assessment:** investigated current crowding, localized Joule heating, peak contact temperature and the thermal paths controlling heat rejection from current-carrying assemblies.
- **Geometry optimisation:** provided design improvements for more uniform current-density distribution through corner-profile refinement and optimisation of welded and bolted contact regions.
- **Contact-interface investigation:** assessed the influence of contact area, conductive path, material selection and interface assumptions on electrical and thermal performance.
- **Test correlation:** compared predicted temperatures with thermocouple measurements, achieving agreement within **±5°C** for the reported application and using the correlation to support geometry and contact-interface decisions.
- **Transferable EHV capability:** apply the same electrical–thermal–fluid reasoning to busbars, terminals and high-voltage connector applications while continuing to deepen utility-specific knowledge in electric-field control, corona/RIV behaviour, insulation coordination and applicable standards.

**Engineering focus:** identifying where electrical losses become heat, how geometry and interfaces create current concentration, how that heat travels through the assembly, and which design changes reduce peak temperature without compromising the current path.

**Methods and tools:** STAR-CCM+, electro-thermal coupling, Joule/Ohmic heating, conjugate heat transfer, current-density interpretation, thermocouple correlation, geometry sensitivity and engineering optimisation.

</details>

<details>
<summary><strong>Automation & simulation methods</strong> — Java, Python, CAD workflows and HPC execution</summary>

### Projects and contribution

- **STAR-CCM+ automation:** developed Java macros for repeatable simulation tasks, including setup, naming and post-processing workflows.
- **Engineering data processing:** used Python to extract results, compare cases, calculate engineering indicators and prepare plots and reports.
- **CAD and preprocessing:** worked on CATIA automation and geometry-handling workflows to reduce repetitive preparation.
- **Simulation execution:** developed and refined SLURM multi-case launch and monitoring workflows, including progress tracking and completion notifications.
- **Methods and infrastructure:** contributed to simulation-method harmonization and compute-environment transitions across collaborating teams.

**Engineering focus:** reducing manual repetition while making assumptions, inputs and results easier to trace. Automation should preserve the checks an engineer needs to trust a result.

**Methods and tools:** Java, Python, CATIA, STAR-CCM+, Bash/SLURM and Excel-based reporting.

[Automation topic notes](https://github.com/maheswaran-pasupathi/maheswaran-pasupathi/blob/main/topics/simulation-automation.md)

</details>

<details>
<summary><strong>Engine & combustion</strong> — in-cylinder CFD, alternative fuels, engine CHT and internal flow</summary>

### Projects and contribution

- **SI/CI in-cylinder simulation:** investigated spray breakup, mixture formation and combustion behaviour, using pressure-trace comparison to assess model agreement with test data.
- **Charge motion and geometry studies:** worked on intake-port and piston-related investigations, examining how flow structures and mixture preparation influence combustion.
- **Alternative fuels:** contributed to diesel, methane and hydrogen combustion studies, considering fuel behaviour, injection strategy and combustion response.
- **Engine thermal and cooling studies:** performed heavy-duty engine CHT, cylinder-head and coolant-jacket investigations to assess temperature distribution, thermal loading and coolant flow.
- **Intake, exhaust and aftertreatment flow:** worked on internal-flow assessment, including pressure losses and flow distribution. For a manifold water-injection question, I used an initial lean model to support the design discussion before increasing fidelity.

**Engineering focus:** linking spray, flow and heat transfer to the design decision, while checking sensitivity to model assumptions and available validation data.

**Methods and tools:** STAR-CCM+, CONVERGE, DOE, charge-motion analysis, combustion modelling, CHT and pressure/temperature comparison.

[Combustion topic notes](https://github.com/maheswaran-pasupathi/maheswaran-pasupathi/blob/main/topics/combustion-powertrain.md) · [Thermal topic notes](https://github.com/maheswaran-pasupathi/maheswaran-pasupathi/blob/main/topics/thermal-multiphysics.md)

</details>

<details>
<summary><strong>AI & engineering computation</strong> — simulation assistance, data-driven models and scientific ML learning</summary>

### Applied work and continuing development

- **Simulation knowledge assistance:** worked on an internal STAR-CCM+ API knowledge-retrieval/RAG approach to support automation and access to technical information.
- **Engineering data workflows:** use Python-based processing and visualization to turn simulation outputs into interpretable comparisons.
- **Knowledge sharing:** discuss AI applications with colleagues and explore where these methods can support engineering productivity.
- **Independent ML development:** build public studies in flow reconstruction, combustion regression and thermal surrogates; these are linked in the open-source section below.
- **Current learning:** geometry-aware modelling, temperature-field prediction, digital twins, physics-informed methods and neural operators.

**Engineering focus:** defining useful inputs and targets, comparing against simple baselines, checking generalization and keeping physical interpretation visible.

**Methods and tools:** Python, NumPy/Pandas, scikit-learn, explainable ML and RAG/LLM workflows.

[Engineering AI topic notes](https://github.com/maheswaran-pasupathi/maheswaran-pasupathi/blob/main/topics/engineering-ai.md)

</details>

## How I work

**Clarify the decision → check the physics → choose model fidelity → analyse → verify and validate → explain uncertainty → automate what is reusable.**

Alongside modelling, I support technical reviews, documentation and methodology alignment across India, Germany and Sweden. My aim is to make the analysis useful to the next engineering decision.

I welcome technical discussions and collaboration around thermal-fluid simulation, automation and engineering AI. [Connect on LinkedIn](https://www.linkedin.com/in/srimahes).

## Open-source projects

My independent public portfolio uses open research datasets to explore how simulation experience translates into reproducible computational studies.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/maheswaran-pasupathi/ai-thermal-fluids/tree/main/projects/01-enginebench-piv"><strong>In-cylinder flow reconstruction</strong></a><br>
<img src="https://raw.githubusercontent.com/maheswaran-pasupathi/ai-thermal-fluids/main/projects/01-enginebench-piv/results/stage3_pod_reconstruction.png" width="100%" alt="EngineBench PIV flow reconstruction compared across POD mode counts"><br>
<sub>Public experimental data: what flow structure survives compression?</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/maheswaran-pasupathi/ai-thermal-fluids/tree/main/projects/03-ecoqube-datacenter-cooling"><strong>Thermal surrogate and cooling exploration</strong></a><br>
<img src="https://raw.githubusercontent.com/maheswaran-pasupathi/ai-thermal-fluids/main/projects/03-ecoqube-datacenter-cooling/results/stage1b_cfd_field_side.png" width="100%" alt="Temperature field rendered from the public ECO-Qube solved CFD case"><br>
<sub>Public CFD and sensor data: where are the hotspots, and what can a surrogate tell us?</sub>
</td>
</tr>
</table>

| Project | What I built | Scope and limitations |
|---|---|---|
| [EngineBench flow reconstruction](https://github.com/maheswaran-pasupathi/ai-thermal-fluids/tree/main/projects/01-enginebench-piv) | POD/PCA, crank-angle regression and reconstruction from incomplete PIV measurements | Documented case study using one operating condition and five crank angles; prediction errors are reported |
| [ECN spray & combustion ML](https://github.com/maheswaran-pasupathi/ai-thermal-fluids/tree/main/projects/02-ecn-spray-combustion) | Lift-off-length regression, SHAP interpretation and held-out nozzle-size checks | Implemented study; feature agreement with expected trends does not establish causality |
| [ECO-Qube cooling surrogate](https://github.com/maheswaran-pasupathi/ai-thermal-fluids/tree/main/projects/03-ecoqube-datacenter-cooling) | CFD/experiment comparison, sensor-based regression and a Streamlit dashboard | Prototype trained on a narrow operating window; optimization uses a convenience proxy, not measured energy savings |

[Browse all projects, code and learning notes](https://github.com/maheswaran-pasupathi/ai-thermal-fluids)

<sub>Professional experience is summarized at a general level. Public projects use open/research data; no proprietary employer data is published here.</sub>

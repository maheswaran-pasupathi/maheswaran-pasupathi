# Maheswaran Pasupathi

### Senior Thermal Specialist – Vehicle & Battery Thermal Management | 1D–3D Simulation
GT-SUITE · HVAC & Battery Cooling · Test Correlation · Product Development

I am a senior thermal specialist with **9 years of experience** in automotive simulation, including six years on TRATON/MAN battery-electric truck and bus programmes. I build and correlate **GT-SUITE 1D vehicle thermal-management models** (cabin HVAC and heat pump, battery and e-powertrain cooling, waste-heat recovery) and couple them with **STAR-CCM+ 3D studies** for battery cooling, thermal propagation and component temperatures. I validate models against climatic wind-tunnel, bench and drive-cycle data, assess duty-cycle energy demand and thermal limits, and turn results into design suggestions. I work within pre-development and development milestones with test, design and quality teams, using Agile practice, Jira and ISO/QMS documentation.

[Experience](#experience) · [Key projects](#key-projects) · [Technical skills](#technical-skills) · [Open-source projects](#open-source-projects) · [LinkedIn](https://www.linkedin.com/in/srimahes)

## Experience

| Role | Systems handled |
|---|---|
| **Senior Thermal Specialist**, MAN Truck & Bus India, Pune (Sep 2024 – present) | Battery-electric truck and bus thermal management: cabin HVAC and heat pump, battery and e-powertrain cooling, waste-heat circuits; 1D vehicle simulation with 1D–3D coupled studies |
| **Assistant Manager → Deputy Manager**, MAN Truck & Bus India, Pune (Apr 2022 – Sep 2024) | 1D vehicle thermal models for electric bus and truck; climatic wind-tunnel and drive-cycle correlation; virtual validation |
| **Senior Engineer**, umlaut, deputed at MAN Truck & Bus India (Jan 2021 – Mar 2022) | Battery cooling and thermal-runaway propagation with 1D system and 3D CHT simulation; Python and Java automation of the simulation workflow |
| **CFD Engineer**, Renault Nissan Technology & Business Centre India, Chennai (Oct 2017 – Jan 2021) | Engine cooling circuits, intake/exhaust and after-treatment airflow, in-cylinder combustion; 3D CFD with test correlation |

Day to day this includes validating results against test data, giving design suggestions, planning deliverables against development milestones, sprint work in Jira, quality and audit-ready documentation, and coordination with the test and design teams in India, Germany and Sweden.

## Key projects

Summarised at a general level. No proprietary employer data is published here.

<details open>
<summary><strong>Full-vehicle 1D thermal model</strong> — cooling, HVAC and energy</summary>

- **Modular vehicle model:** GT-SUITE model linking drive cycle, battery (electrical and thermal), motor, cooling circuits, refrigerant/HVAC circuit and controls, with variant handling and version control so one model serves several configurations.
- **Studies:** duty-cycle energy demand and thermal limits, battery thermal insulation and pre-conditioning energy, DOE over vehicle configurations, and cooling performance under different fan operating modes.

**Methods and tools:** GT-SUITE, MATLAB/Simulink, Python

</details>

<details>
<summary><strong>Vehicle HVAC and heat-pump modes</strong> — 1D model and test correlation</summary>

- **Operating modes:** cabin heating and cooling modes (waste-heat recovery, electric heater, heat pump, battery-assisted cooling) with pump, valve, compressor and heater control logic, compared on energy demand and cabin and battery temperature.
- **Correlation:** cabin, vent, refrigerant and coolant states compared with climatic wind-tunnel heating tests and drive data; gaps closed through boundary-condition and parameter review; 1D–3D cabin coupling for temperature distribution.

**Methods and tools:** GT-SUITE, MATLAB/Simulink, Python

</details>

<details>
<summary><strong>Battery performance in cold ambient</strong> — recuperation, heating strategy and insulation</summary>

- **Constraints:** how heating capacity, coolant-circuit temperature limits, motor boundaries and battery recuperation limits restrict vehicle performance across ambient temperature.
- **Strategies:** thermal insulation compared with electric and waste-heat heating through sensitivity studies, with assumptions, limits and open points documented.

**Methods and tools:** GT-SUITE, Python

</details>

<details>
<summary><strong>Battery cooling</strong> — 1D networks and 3D CHT</summary>

- **Assessment:** peak temperature and spread, branch-flow distribution, circuit pressure loss, pump operating point and cold-plate performance, using a 1D coolant network with 3D conjugate heat transfer.
- **Concepts:** individual-cell cooling compared with pack-level cooling for temperature uniformity; radiator and chiller operation for shared battery and cabin demand and auxiliary energy.

**Methods and tools:** GT-SUITE, STAR-CCM+

</details>

<details>
<summary><strong>Battery thermal runaway</strong> — 3D CFD and 1D propagation</summary>

- **Method:** hybrid empirical and 3D CFD approach to thermal-propagation risk at cell and module level.
- **Correlation:** coupled 3D–1D propagation simulations compared with calorimeter data, reviewing inter-cell heat paths and cooling conditions.

**Methods and tools:** STAR-CCM+, GT-SUITE

</details>

<details>
<summary><strong>High-current charging cable and connector</strong> — 1D thermal simulation</summary>

- **Models:** GT-SUITE 1D thermal models of a DC charging cable and connector, checked against published data for temperature distribution, ampacity and energy balance.
- **Liquid cooling:** the method extended to a liquid-cooled cable to quantify the gain in current-carrying capacity.

**Methods and tools:** GT-SUITE

</details>

## Technical skills

| Area | Tools and topics |
|---|---|
| Thermal systems | GT-SUITE · Simcenter AMESim · MATLAB/Simulink · Modelica |
| CAD / CAE | STAR-CCM+ · CATIA · ENOVIA · Ansys SpaceClaim · Ansys Workbench |
| Simulation domains | Vehicle thermal model · HVAC systems · Battery cooling · 1D–3D coupling · Battery safety simulation |
| Test correlation | Climatic wind tunnel · Drive/duty cycle · Energy balance · Thermocouple/calorimeter data · Sensitivity analysis |
| DOE & optimisation | Design of Experiments · Parametric studies · Reduced-order/surrogate models |
| Automation | Python · Java macros (STAR-CCM+) · C++ · Climate and route APIs · PyBaMM |
| AI / ML | Scikit-learn · PyTorch · Keras · LLM · RAG |
| Process & Agile | Power BI · SQL · Power Apps · Power Automate · Jira · Agile/Sprint · ISO/QMS |
| Product development | Pre-development · Development milestones · Design and test coordination · Document release |
| Problem solving | TRIZ · SCAMPER · Conceptual thinking · Root-cause analysis |

## Related work

Earlier and adjacent work, kept for reference.

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

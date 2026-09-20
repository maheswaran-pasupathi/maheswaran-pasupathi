# Maheswaran Pasupathi

### Battery & Vehicle Thermal Expert | System-Level 1D–3D Simulation
Senior Thermal Specialist · GT-SUITE · STAR-CCM+ · HVAC & Battery Cooling · Test Correlation

I am a battery and vehicle thermal management engineer with **9 years of experience** in automotive simulation, including six years on TRATON/MAN battery-electric truck and bus programmes. I build and correlate **GT-SUITE 1D vehicle thermal-management models** (cabin HVAC and heat pump, battery and e-powertrain cooling, waste-heat recovery) and couple them with **STAR-CCM+ 3D studies** for battery cooling, thermal propagation and component temperatures. I validate models against climatic wind-tunnel, bench and drive-cycle data, assess duty-cycle energy demand and thermal limits, and turn results into design suggestions. I work within pre-development and development milestones with test, design and quality teams, using Agile practice, Jira and ISO/QMS documentation.

[Experience](#experience) · [Key projects](#key-projects) · [Public projects](#public-projects) · [Technical skills](#technical-skills) · [LinkedIn](https://www.linkedin.com/in/srimahes)

## Experience

| Role | Systems handled |
|---|---|
| **Senior Thermal Specialist**, MAN Truck & Bus India, Pune (Sep 2024 – present) | Battery-electric truck and bus thermal management: cabin HVAC and heat pump, battery and e-powertrain cooling, waste-heat circuits; 1D vehicle simulation with 1D–3D coupled studies |
| **Assistant Manager → Deputy Manager**, MAN Truck & Bus India, Pune (Apr 2022 – Sep 2024) | 1D vehicle thermal models for electric bus and truck; climatic wind-tunnel and drive-cycle correlation; virtual validation |
| **Senior Engineer**, umlaut, deputed at MAN Truck & Bus India (Jan 2021 – Mar 2022) | Battery cooling and thermal-runaway propagation with 1D system and 3D CHT simulation; Python and Java automation of the simulation workflow |
| **CFD Engineer**, Renault Nissan Technology & Business Centre India, Chennai (Oct 2017 – Jan 2021) | Powertrain cooling circuits and airflow; 3D CFD with test correlation |

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

## Public projects

Small, reproducible studies with generic numbers, in the same areas as the work above.

| Project | Topic |
|---|---|
| [Battery heat and coolant sizing](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/01-battery-heat-and-coolant-sizing) | Heat per cell and pack, coolant flow, temperature rise with no cooling |
| [Coolant flow distribution](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/02-cooling-plate-flow-distribution) | Pump operating point, U-type and Z-type headers, orifice balancing |
| [Pack temperature and cooling strategy](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/03-pack-temperature-cooling-strategy) | Radiator against chiller over a hot-day route, and the energy cost |\n| [Shared battery + cabin cooling](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/04-shared-battery-cabin-cooling) | Shared refrigeration capacity, COP, compressor power and condenser rejection |
| [Air-cooled 18650 cell CHT benchmark](https://github.com/maheswaran-pasupathi/starccm-cht-benchmarks) | STAR-CCM+ conjugate heat transfer checked against published data |

All of them are in the [battery-vehicle-thermal-lab](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab) repository, with more on the way.

## Technical skills

| Area | Tools and topics |
|---|---|
| Thermal systems | GT-SUITE · Simcenter AMESim · MATLAB/Simulink · Modelica |
| CAD / CAE | STAR-CCM+ · CATIA · ENOVIA · Ansys SpaceClaim · Ansys Workbench |
| Simulation domains | Vehicle thermal model · HVAC systems · Battery cooling · 1D–3D coupling · Battery safety simulation |
| Test correlation | Climatic wind tunnel · Drive/duty cycle · Energy balance · Thermocouple/calorimeter data · Sensitivity analysis |
| DOE & optimisation | Design of Experiments · Parametric studies · Reduced-order/surrogate models |
| Automation | Python · Java macros (STAR-CCM+) · C++ · Climate and route APIs · PyBaMM |
| Process & Agile | Power BI · SQL · Power Apps · Power Automate · Jira · Agile/Sprint · ISO/QMS |
| Product development | Pre-development · Development milestones · Design and test coordination · Document release |
| Problem solving | TRIZ · SCAMPER · Conceptual thinking · Root-cause analysis |

## How I work

**Clarify the decision → check the physics → choose model fidelity → analyse → verify and validate → explain uncertainty.**

Alongside modelling, I support technical reviews, documentation and methodology alignment across India, Germany and Sweden. My aim is to make the analysis useful to the next engineering decision.

I welcome technical discussions around battery cooling, vehicle thermal management and system-level simulation. [Connect on LinkedIn](https://www.linkedin.com/in/srimahes).

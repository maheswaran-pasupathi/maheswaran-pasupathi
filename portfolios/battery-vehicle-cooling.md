# Battery & Vehicle Cooling Portfolio

**Focus:** keeping the battery, e-powertrain and cabin within thermal limits while controlling auxiliary energy across driving, charging and ambient conditions.

This is a vehicle-level thermal-management portfolio: system architecture and controls in 1D, resolved local thermal-fluid behaviour in 3D, and correlation/verification before design decisions.

## Industrial keywords

Battery thermal management · vehicle thermal management · battery cooling · e-powertrain cooling · cold plate · coolant distribution · pressure loss · pump operating point · radiator · chiller · condenser · cabin HVAC · heat pump · compressor power · COP · thermal controls · drive cycle · charging · pre-conditioning · waste-heat recovery · thermal uniformity · maximum temperature · energy consumption · climatic correlation · 1D–3D coupling

## Relevant 1D activities

| Activity | Typical decision |
|---|---|
| Coolant and refrigerant circuit architecture | How should battery, e-powertrain and cabin loops be connected? |
| Component maps and control logic | What pump, fan, compressor and valve strategy meets thermal targets with minimum energy? |
| Drive-cycle and charging simulation | What happens during hot ambient, hill, high-speed, idle or DC-fast-charge cases? |
| Radiator/chiller/HVAC capacity study | Is the limitation heat-exchanger capacity, flow distribution or control strategy? |
| 1D–3D data exchange | Which flow rates and boundary conditions require a local 3D study, and what reduced parameters return to the system model? |
| Test correlation and sensitivity | Which boundary conditions or uncertain parameters materially affect the conclusion? |

## Relevant 3D activities

| Activity | Typical decision |
|---|---|
| Pack and cold-plate CHT | Are local cell/module temperatures and thermal gradients acceptable? |
| Coolant distribution and pressure loss | Do branches receive the intended flow, and where are restrictions needed? |
| E-motor/inverter or component cooling | Which surface, jacket or interface drives the local hotspot? |
| Radiator/condenser airflow | How do airflow, fan operation and packaging affect heat rejection? |
| Cabin or underhood thermal study | Where are recirculation, non-uniformity or heat-soak risks? |
| Transient CHT | Does temperature response under a duty cycle match the time available for control action? |

## Demonstrated engineering evidence

- Battery cell/module/pack cooling studies combining 1D coolant-network behaviour with 3D CHT for temperature, distribution and pressure-loss assessment.
- Vehicle HVAC and heat-pump system studies covering cabin/battery interactions, waste-heat recovery, controls and duty-cycle energy demand.
- Battery thermal-propagation studies using 1D system and 3D thermal approaches, with calorimeter/thermocouple correlation context.

## Public projects

- [Battery heat and coolant sizing](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/01-battery-heat-and-coolant-sizing)
- [Coolant-flow distribution](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/02-cooling-plate-flow-distribution)
- [Pack cooling strategy](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/03-pack-temperature-cooling-strategy)
- [Shared battery + cabin cooling](https://github.com/maheswaran-pasupathi/battery-vehicle-thermal-lab/tree/master/projects/04-shared-battery-cabin-cooling)

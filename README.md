## Mohamed Al-Mandhari

**Energy systems engineer. I build open, tested models of energy systems and use them to answer design questions.**

My work sits where physical models meet data: batteries and electrolysers, buildings and multi-energy neighbourhoods, distribution grids and wind turbines, from component physics to optimisation, machine learning and validation against measurements. I am on the Erasmus Mundus DENSYS Master's (Université de Lorraine, now Politecnico di Torino) and hold a first-class BEng in Renewable Energy Engineering from the University of Exeter.

**Looking for:** a six-month Master's thesis internship from March 2027 (mid-February possible), with a PhD as the next step.

---

### Featured work

**[muscat-energy-hub](https://github.com/Malmand/muscat-energy-hub)** · *How much model detail does a sizing study need?*  
A district-cooled neighbourhood with PV, battery, chiller, chilled-water tank and a PEM electrolyser, sized with a simple and a detailed model of every component. Most details barely move the design; the buildings' thermal mass cuts the optimal tank by 39%. Includes new, tested OMEGAlpes units for a chiller and an electrolyser.  
`Pyomo` `HiGHS` `OMEGAlpes` `uncertainty analysis`

**[building-digital-twin-kalman](https://github.com/Malmand/building-digital-twin-kalman)** · *A digital twin kept in step with a real building*  
Grey-box thermal models of 23 office zones identified from 18 months of open measured data (CU-BEMS), run online as an extended Kalman filter. The synchronised twin forecasts, detects faults and tests demand-response scenarios; a hybrid with gradient boosting beats both physics and machine learning alone.  
`Kalman filter` `grey-box models` `XGBoost` `demand response`

**[lv-grid-copper-or-flexibility](https://github.com/Malmand/lv-grid-copper-or-flexibility)** · *Copper or flexibility? Long-term LV planning*  
Three SimBench feeders planned from 2025 to 2045 with full-year power flows: cables and transformers against §14a control, a battery and a tap-changing transformer, compared on cost, life-cycle CO2, metals and regret with WSM, TOPSIS, PROMETHEE II and SMAA-2.  
`pandapower` `LCA` `MCDA` `SMAA`

**[wind-fleet-instability-monitoring](https://github.com/Malmand/wind-fleet-instability-monitoring)** · *Turbine loads from SCADA data*  
Detection of edgewise blade instabilities and their fatigue cost across a fleet, and a machine-learning load emulator for power de-rating, checked against real 20 Hz measurements of a research turbine.  
`SQL` `SciPy` `XGBoost` `rainflow`

**[hybrid-energy-storage-pybamm](https://github.com/Malmand/hybrid-energy-storage-pybamm)** · *From cell physics to a sized storage system*  
A PyBaMM model calibrated on experimental data, reduced to a fast equivalent circuit, and used to size a battery and supercapacitor system for frequency reserve, re-checked on a year of measured grid frequency. Exported as an FMI 2.0 FMU.  
`PyBaMM` `FMI` `co-simulation`

**[residential-microgrid-ems](https://github.com/Malmand/residential-microgrid-ems)** · *Home energy management, end to end*  
PV, battery, bidirectional EV and heat pump: MILP control, annual sizing, forecast-driven MPC, coupling with AC load flow on a feeder, and automated tests of a battery controller.  
`Pyomo` `XGBoost` `pandapower`

### More projects

- **[ptx-methanol-surrogate](https://github.com/Malmand/ptx-methanol-surrogate)**: physics-constrained machine-learning surrogates of a power-to-methanol reactor, trained on noisy operating logs simulated with a kinetic plant model.
- **[pv-pem-electrolyser-degradation](https://github.com/Malmand/pv-pem-electrolyser-degradation)**: a year of PV-driven PEM electrolyser performance and ageing in Oman and the UK; code for an *Energies* Editor's Choice article.
- **[energy-time-series-transfer-learning](https://github.com/Malmand/energy-time-series-transfer-learning)**: household PV and load forecasting with LSTM and Transformer models, transfer learning, and EV and heat-pump detection from meter data.
- **[AEM_Case_based](https://github.com/Malmand/AEM_Case_based)**: electrochemical and thermal model of an AEM water electrolyser, calibrated on polarisation and EIS data.

### Publications

- **Al-Mandhari, M.**, Ghosh, A. (2025). Modelling solar intermittency effects on PEM electrolyser performance and degradation: a comparison of Oman and UK. *Energies* 18, 6131. [doi](https://doi.org/10.3390/en18236131) · *Editor's Choice*
- **Al-Mandhari, M.** et al. (2026). Floating photovoltaic-powered green hydrogen for decarbonization of the energy-consuming sectors in the United Kingdom. *Energies* 19, 2931. [doi](https://doi.org/10.3390/en19122931)
- Sanders, C. et al., incl. **Al-Mandhari, M.** (2026). From pasture to platform: integrating agrivoltaics and green hydrogen for the Penzance-London railway corridor. *Solar Energy* 318, 115064. [doi](https://doi.org/10.1016/j.solener.2026.115064)

More on [ORCID](https://orcid.org/0009-0000-8533-8702).

### Toolbox

**Modelling and optimisation:** Python, Pyomo, OMEGAlpes, HiGHS, Gurobi, PyBaMM, pandapower, SimBench, MATLAB/Simulink, FMI  
**Decision support:** multi-criteria analysis (WSM, TOPSIS, PROMETHEE, SMAA), life-cycle assessment  
**Data and machine learning:** pandas, SQL, scikit-learn, XGBoost, PyTorch, TensorFlow, uncertainty and sensitivity analysis  
**Energy tools:** pvlib, PVsyst, HOMER Pro, QGIS, openLCA, GaBi

### Contact

[LinkedIn](https://www.linkedin.com/in/mohamed-al-mandhari) · [ORCID](https://orcid.org/0009-0000-8533-8702) · e66840u@etu.univ-lorraine.fr

Arabic (native) · English (professional) · French (A2, learning)

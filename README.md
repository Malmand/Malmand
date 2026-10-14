## Hi, I'm Mohamed Al-Mandhari

Energy systems engineer working where **physical models meet data**: energy storage, Power-to-X, local energy systems and wind, from cell and reactor models to optimisation, machine learning and automated monitoring tools.

- Erasmus Mundus Master's in Decentralised Smart Energy Systems (DENSYS): Université de Lorraine (M1, Très Bien), now at Politecnico di Torino, Energy Storage and Power-to-X track
- BEng Renewable Energy Engineering, University of Exeter (First-Class Honours)
- Peer-reviewed publications on PV, floating PV, agrivoltaics and green hydrogen
- Looking for a six-month Master's thesis internship from March 2027 (mid-February possible), and interested in continuing to a PhD

### Projects

**Energy storage and Power-to-X**

| Project | What it does | Stack |
|---|---|---|
| [hybrid-energy-storage-pybamm](https://github.com/Malmand/hybrid-energy-storage-pybamm) | PyBaMM battery model calibrated against experimental data, reduced to equivalent-circuit models, and used to size a battery-supercapacitor system and its energy management; plant exported as an FMI 2.0 FMU | Python, PyBaMM, pythonfmu, fmpy |
| [ptx-methanol-surrogate](https://github.com/Malmand/ptx-methanol-surrogate) | Power-to-methanol reactor: cleaning noisy operational logs, physics-constrained ML surrogates that respect mass balances and equilibrium, and an optimiser for operating parameters | Python, scikit-learn, SciPy |
| [pv-pem-electrolyser-degradation](https://github.com/Malmand/pv-pem-electrolyser-degradation) | Year-long PV-PEM electrolyser simulation of performance and degradation, Oman vs UK; code for an *Energies* Editor's Choice article | Python, pvlib |
| [AEM_Case_based](https://github.com/Malmand/AEM_Case_based) | AEM water electrolyser model: electrochemical fitting, 1D thermal model, efficiency, wet vs dry cathode, EIS calibration | Python, SciPy |

**Optimisation, control and grids**

| Project | What it does | Stack |
|---|---|---|
| [residential-microgrid-ems](https://github.com/Malmand/residential-microgrid-ems) | Home microgrid with PV, battery, bidirectional EV and heat pump: rule-based vs MILP control, annual sizing, XGBoost forecast-driven MPC, dispatch coupled with AC load flow on an LV feeder, and automated closed-loop tests of a battery site controller | Python, Pyomo, HiGHS, XGBoost, pandapower |

**Data, machine learning and monitoring**

| Project | What it does | Stack |
|---|---|---|
| [wind-fleet-instability-monitoring](https://github.com/Malmand/wind-fleet-instability-monitoring) | Wind fleet analysis: SQL database of SCADA data, data-quality checks, detection of edgewise blade instabilities, rainflow fatigue impact, KPIs and a digital-twin adapter; plus a machine-learning load emulator for power de-rating transients, built on a BEM-based reduced-order aero-servo-elastic turbine model and validated on prototype-style field data | Python, SQL, SciPy, XGBoost, rainflow |
| [energy-time-series-transfer-learning](https://github.com/Malmand/energy-time-series-transfer-learning) | Household PV and grid-import forecasting with LSTM and Transformer models and transfer learning; identifying EV charging and heat-pump use from smart-meter data alone | PyTorch, TensorFlow, XGBoost |

### Selected publications

- **Al-Mandhari, M.**, Ghosh, A. (2025). Modelling solar intermittency effects on PEM electrolyser performance and degradation: a comparison of Oman and UK. *Energies*, 18(23), 6131. [doi:10.3390/en18236131](https://doi.org/10.3390/en18236131) · *Editor's Choice*
- **Al-Mandhari, M.**, Morton, L., Hussain, S.N., Zhou, Z., Chew, Z.J., Ghosh, A. (2026). Floating photovoltaic-powered green hydrogen for decarbonization of the energy-consuming sectors in the United Kingdom. *Energies*, 19(12), 2931. [doi:10.3390/en19122931](https://doi.org/10.3390/en19122931)
- Sanders, C., Betts, H., Hussain, S.N., **Al-Mandhari, M.**, Ghosh, A. (2026). From pasture to platform: integrating agrivoltaics and green hydrogen for the Penzance-London railway corridor. *Solar Energy*, 318, 115064. [doi:10.1016/j.solener.2026.115064](https://doi.org/10.1016/j.solener.2026.115064)
- Coleneso, D., **Al-Mandhari, M.**, Hussain, S.N., Ghosh, A. (2026). Vehicle-integrated photovoltaics (VIPV) in electrified mobility: a structured systematic review of technical performance, system integration, and strategic deployment. *Solar*, 6(3), 26. [doi:10.3390/solar6030026](https://doi.org/10.3390/solar6030026)
- Hussain, S.N., **Al-Mandhari, M.**, Ali, S.M.F., Zaib, A., Ghosh, A. (2026). GIS-driven regional assessment for sustainable data center siting in the United Kingdom. *Land*, 15(3), 516. [doi:10.3390/land15030516](https://doi.org/10.3390/land15030516)

Full list on [ORCID](https://orcid.org/0009-0000-8533-8702).

### Tools

**Modelling and optimisation:** Python, Pyomo (MILP/LP), HiGHS, Gurobi, SciPy, PyBaMM, pandapower, MATLAB/Simulink, FMI/FMU · **Data and ML:** pandas, NumPy, SQL, scikit-learn, XGBoost, PyTorch, TensorFlow · **Signal processing and fatigue:** filtering, envelope and spectral analysis, rainflow counting · **Energy tools:** pvlib, PVsyst, HOMER Pro, QGIS, GaBi, openLCA

### Contact

[LinkedIn](https://www.linkedin.com/in/mohamed-al-mandhari) · [ORCID](https://orcid.org/0009-0000-8533-8702)

Languages: Arabic (native), English (professional), French (A2, learning)

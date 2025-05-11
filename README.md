# MATXCOM—an x-ray/gamma-ray attenuation calculator for arbitrary materials

[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)
[![Try Web App](https://img.shields.io/badge/Try%20Online-MATXCOM-brightgreen.svg)](https://matxcom.net/)

MATXCOM is a specialized program developed for the calculation of x-ray and gamma-ray interaction cross-sections and attenuation parameters for arbitrary materials. Based on the EPICS2023 evaluated photon data library (EPDL), MATXCOM calculates the following properties:
- Mass attenuation coefficient (MAC)
- Linear attenuation coefficient (LAC)
- Half and tenth value layers (HVL and TVL)
- Mean free path (MFP)
- Effective atomic number (Z<sub>eff</sub>)
- Total atomic and electronic cross-sections (ACS and ECS)
- Effective electron density (N<sub>eff</sub>)
- Effective conductivity (C<sub>eff</sub>)
- Geometric progression fitting parameters (a, b, c, d, and X<sub>k</sub>)
- Energy absorption and exposure buildup factors (EABF and EBF)

> **Note:** The latest release also includes support for the XCOM/NIST Standard Reference Database 8 (XGAM) data library as an alternative to EPICS2023/EPDL.

> **Web Version Now Available!** MATXCOM can now be used directly from web browser: [Launch Web App](https://matxcom.net/). This is the most user-friendly and recommended way to use MATXCOM (same backend as the command-line version).

## Installation
The compiled version of MATXCOM is available in the [Releases](https://github.com/saad589/matxcom/releases) section. Simply download the file and follow the installation guide provided in the [User's Guide](https://saad589.github.io/matxcom/).

## Usage
Download the latest release and follow the input format specified in the [User's Guide](https://saad589.github.io/matxcom/).

## Citation
If you use MATXCOM in your research, please cite the associated publication:

Islam, Saad. "MATXCOM—an x-Ray/Gamma-Ray Attenuation Calculator for Arbitrary Materials Based on EPICS2023 Evaluated Photon Data Library". *Radiation Physics and Chemistry*, vol. 229, 2025, p. 112433, [https://doi.org/10.1016/j.radphyschem.2024.112433](https://doi.org/10.1016/j.radphyschem.2024.112433).

Full-text available on [ResearchGate](https://www.researchgate.net/publication/386224289_MATXCOM-an_x-raygamma-ray_attenuation_calculator_for_arbitrary_materials_based_on_EPICS2023_evaluated_photon_data_library). 

## License
This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/) license.

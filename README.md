# ViscoCalc v1.0

This Matlab app allows the calculation of viscosity of silicate melts using two popular viscosity models by Giordano et al., 2008 (EPSL) and Hui & Zhang, 2007 (GCA) via an user-friendly GUI. 
Melt composition and temperature are input parameters. Alternatively, exemplary compositions can be chosen from a dropdown menu which also allows the import of user data (must be the same order of oxides). 
Further, glass transition temperatures and the fragility index are calculated. Viscosities are displayed in log (Pa s) and also plotted over a wide temperature range.
Results can be easily saved to an excel file, which contains the logViscosity over the temperature range. Please refer to the original papers to check the limitations of each viscosity model (e.g., valid temperature range). 

Installation:

Open the "ViscoCalc.mlappinstall" file in MATLAB. The app will be installed by Matlab and added to the Apps toolbar.

Features:
- Input = temperature + melt composition (direct user input, example compositions, or import of user data)
- Two ways of normalization to 100% (either normalizing all oxides to sum up to 100% or 100-H2O)
- Calculate viscosity from both models for a temperature range + the specified temperature
- Calculate glass transition temperatures and fragility index
- Plot results (logn vs. 1/T)
- Save results to an excel file (filename can be defined via text input); the file will be created in the active folder

Please report bugs to: thilo.bissbort@rub.de

All credits go to Giordano et al. (2008) and Hui and Zhang (2007) for developing these neat models!

References:

- Giordano, D.; Potuzak, M.; Romano, C.; Dingwell, D. B.; Nowak, M. (2008): Viscosity and glass transition temperature of hydrous melts in the system CaAl2Si2O8–CaMgSi2O6. In: Chemical Geology 256, 3, S. 203–215.
- Hui, H.; Zhang, Y. (2007): Toward a general viscosity equation for natural anhydrous and hydrous silicate melts. In: Geochimica et Cosmochimica Acta 71, 2, S. 403–416.

PS: I am not responsible for any errors, mistakes, software or hardware problems that might be caused by using this program. 

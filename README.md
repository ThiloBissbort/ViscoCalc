# ViscoCalc v1.0

This Matlab app allows the calculation of viscosity of silicate melts using two popular viscosity models by Giordano et al., 2008 (EPSL) and Hui & Zhang, 2007 (GCA) via an user-friendly GUI. 
Melt composition and temperature are input parameters. Alternatively, exemplary compositions can be chosen from a dropdown menu which also allows the import of user data (must be the same order of oxides). 
Further, glass transition temperatures and the fragility index are calculated. Viscosities are displayed in log (Pa s) and also plotted over a wide temperature range.
Results can be easily saved to an excel file, which contains the logViscosity over the temperature range. Please refer to the original papers to check the limitations of each viscosity model (e.g., valid temperature range). 

Features:
- Input = temperature + melt composition (direct user input, example compositions, or import of user data)
- Two ways of normalization to 100% (either normalizing all oxides to sum up to 100% or 100-H2O)
- Calculate viscosity for both models for a temperature range + the specified temperature
- Calculate glass transition temperatures
- Plot results (logn vs. 1/T)
- Save results to an excel file (filename can be defined via text input)

Please feel free to play around and report bugs to: thilo.bissbort@rub.de



PS: I am not responsible for any errors, mistakes, software or hardware problems that might be caused by using this program. 

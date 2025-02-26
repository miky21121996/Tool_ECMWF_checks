# Tool_ECMWF_checks
A python tool for checking ECMWF netcdf data in terms of statistics wrt climatology, developed at CMCC Foundation.

## how to get the code
```bash
git clone git@github.com:miky21121996/Tool_ECMWF_checks.git $YOUR_INSTALL_DIR
```

## capabilities of the tool

The tool is in fact a jupyter notebook that allows to compute:
- Climatology of T2M, D2M, MSL, U10M and V10M based on user preferences, which are defined in a specific configuration cell of the notebook. It generates a netcdf file and some plots for each climatological variable.
- Time series and 2D maps for comparison between the computed climatology and a new time series of ECMWF data chosen by the user, setting the time period in a specific cell of the notebook

For futher info and visualization of example plots and settings look at the pdf Tool for [ECMWF atmospheric fields checks wrt climatology.pptx](https://github.com/miky21121996/Tool_ECMWF_checks/blob/master/Tool%20for%20ECMWF%20atmospheric%20fields%20checks%20wrt%20climatology.pptx)

Interactive Plot Example Screenshot:
![image](https://github.com/user-attachments/assets/168823e3-309b-4dd3-9a53-2e6cf27b60b3)

To interact with the plot, download the raw html file and open it on browser

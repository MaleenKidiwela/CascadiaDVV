# CascadiaDVV

This Repository contains the data products, analysis and scripts for the Ambient Noise Interferometry Project for the OOI and ONC-NEPTUNE cabled array seismometers. It uses a clone of Seisnoise.jl and SeisDVV.jl and improves upon usability in submarine environments. Each notebook listed within the repository is a script for performing the data analysis workflow

Main dv/v timeseries and their correlation coefficient mean from the analysis is stored in DVV_results folder

1. streaming_data.ipynb - Streams Broadband data and stores
2. Save_Correlation.ipynb - Performs correlation and saves
3. DVV final code.ipynb - Runs dv/v using the correlation function one correlation function at a time
4. Interstation HYSB1_HYS14.ipynb - Runs dv/v for interstation correlation function between HYSB1 and HYS14
5. HYSB1 SEASONALITY.ipynb - plots HYSB1 dv/v timeseries for < 1Hz and removes seasonality from dv/v
6. NC89 SEASONALITY.ipynb - plots NC89 dv/v timeseries for < 1Hz and removes seasonality from dv/v
7. AnalyzePressurePulse.ipynb - Plots and analyze fluid pulses observed in HYSB1 and HYS14
8. Pressure Pulse Narrow Freq.ipynb - Plotting and comparing dv/v from narrow frequency bands
9. Synthetic DVV Final.ipynb - dv/v for synthetic correlation function from wmsan
10. Figures for Manuscript.ipynb/ Final Plots.ipynb/Migration Plots.ipynb - plots for dv/v
11. Tremorclust.ipynb - clustering deep PNSN tremor
12. synthetic_CC.ipynb - wmsan notebook

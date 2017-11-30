# SimulatorInR

This repository holds various simulator dashboard in R and RStudio !!!

To use simulator:

1) Download intrest Simulator.

2) Make Sure atleast following basic packages are installed:
library(flexdashboard)
library(ggplot2)
library(ggthemes)
library(plotly)
library(gridExtra)
library(RColorBrewer)

3) Once you have above, use 'Run Document' or 'Knit' directly from RStudio to start the simulator.

Njoy Simulating! :)

## For Curve Simulator
'val' denotes x as in cos(x)
'valGen', 'valSin', 'valCos', 'valPow', 'valLog', 'valExp' are addition to 'val' as in cos(val,valCos) will be evaluated as cos(x+ valCos)

Examples:
Set 'Curve' to 'Generic Curve' and copy paste following in 'Enter Expression': 

pow(cos(exp(val)),valPow) + log(val,valLog) 

and play with Log Value Diff & Power Value Diff to see some beautiful curves. You can change range of values to between -6 to 10 to see ful scope.

## For Distribution Simulator
Just Download the Simulator and run it.
This is still in WIP but we can Plots can explain behaviour significantly. Also help on distribution is available in tab to rescue.

# SimulatorInR
This repository holds various simulator dashboard in R

## For Curve Simulator
'val' denotes x as in cos(x)
'valGen', 'valSin', 'valCos', 'valPow', 'valLog', 'valExp' are addition to 'val' as in cos(val,valCos) will be evaluated as cos(x+ valCos)

Examples:
Set 'Curve' to 'Generic Curve' and copy paste following in 'Enter Expression': 

pow(cos(exp(val)),valPow) + log(val,valLog) 

and play with Log Value Diff & Power Value Diff to see some beautiful curves. You can change range of values to between -10 to 10 to see ful scope.

# MATLAB Functions

## Function Types  
- [Analytics](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Analytics) - functions that return a graphical `Display` response
- [Bars](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Bars) - functions that manipulate or parse a given vector or matrix of price observations (`Open | High | Low | Close`)
- [Elementals](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Elementals) - functions that are **fundamental atomic** calculations
- [Email](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Email) - Generic functions for email notifications
- [ImportExport](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/ImportExport) - Functions that provide for the import or export of data
- [PAR](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/PAR) - Wrappers for the parallel processing of vectorized parametric calculations (`optimizations`)
- [Printing and Display](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Printing%20and%20Display) - Functions that provide user feedback during processing
- [Signal Aggregators](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Signal%20Aggregators) - Aggregators take two or more `State` functions and combines them logically to create an aggregate `Signal` output
- [Signals](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Signals) - Functions that output an actionable array of `Signals` that should be passed to a P&L function for analysis
- [States](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/States) - Functions that output a boolean array of a logical test results per observation (Open ![Image](http://mathurl.com/q66m8ot.png) Close)
- [Utilities](https://github.com/mtompkins/openAlgo/tree/master/Matlab/Functions/Utilities) - Functions that call to operating system low level actions

## Naming Convention

| Name Style | Description |
| ---------- | ----------- |
|function|`Elemental` or generic function|
|functionDIS|`Display` function|
|functionPAR|`PAR` function|
|functionSIG|`Signal` function|
|functionSTA|`State` function|
|functionFunctionSIG|`Signal` aggregator function|
|functionFunctionSTA|`State` aggregator function|  

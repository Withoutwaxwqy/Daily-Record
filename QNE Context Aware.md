# QNE Context Aware

### TODO    
- [ ] plot the lines of `vis-satellite number`, `DOP`, `obs per slips`, `unvis-angle`, `CN0`, `average elevation of satellite`
- [ ] statitics analysis
- [ ] add classification analysis in QNE algorithm

## plot the lines of indicators
add debug message in post-processing algorithm.
format as 
```
[Tobey Debug] vis-satellite number: %d, DOP:%.3f, obs per slips:%d, unvis-angle:%f, average CN0:%f, average elevation of satellite:%f;
[Tobey Debug] vis-satellite number: 50, DOP:1.105, obs per slips:1220, unvis-angle:122, average CN0:40.3, average elevation of satellite:22.33;
```
![](./picture)
To get these indicators, calculation is needed if no value in the algorithm.

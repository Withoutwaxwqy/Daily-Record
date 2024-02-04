# QNE Context Aware

### TODO    
- [x] [select indicators](#select-indicators)
- [ ] [plot the lines of **`vis-satellite number`**, `DOP`, `obs per slips`, `unvis-angle`, `CN0`, `average elevation of satellite`](#plot-the-lines-of-indicators)
- [ ] [statitics analysis](#statitics-analysis)
- [ ] [add classification analysis in QNE algorithm](#add-classification-analysis-in-qne-algorithm)

## select indicators   
add `debug` message in post-processing algorithm.
format as 
```
[T Debug] tor:%f, vis-satellite number: %d, DOP:%.3f,  obs per slips:%d,   unvis-angle:%f,  average CN0:%f,   average elevation of satellite:%f;
[T Debug] tor:%f, vis-satellite number: 50, DOP:1.105, obs per slips:1220, unvis-angle:122, average CN0:40.3, average elevation of satellite:22.33;
```

## plot the lines of indicators

To get these indicators, calculation is needed if no value in the algorithm.

## statitics analysis

## add classification analysis in QNE algorithm

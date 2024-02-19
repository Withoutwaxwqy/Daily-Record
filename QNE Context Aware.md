# QNE Context Aware

### TODO    
- [x] [select indicators](#select-indicators)
- [ ] [plot the lines of **`vis-satellite number`**, `DOP`, `obs per slips`, `unvis-angle`, `CN0`, `average elevation of satellite`](#plot-the-lines-of-indicators)
- [ ] [statitics analysis](#statitics-analysis)
- [ ] [add classification analysis in QNE algorithm](#add-classification-analysis-in-qne-algorithm)

## select indicators   
|indicators|status|
|------------|----|
|cycleSlipratio|**ready** 🎉|
|average CN0 |**ready** 🎉|
|average Elevation|**ready** 🎉|
|valid carrier phase number|**ready** 🎉|
|**average Elevation of valid carrier phase**</br>   which is the most intuitive|**ready** 🎉|
|vis satellite num|~~need to **add**~~ use `int n ` as vis satellite num|
|DOP|**ready** 🎉|
|[unvis angle](https://github.com/Withoutwaxwqy/Daily-Record/blob/main/Context-aware.md#airticals)|UNDO|
|MP etc.||



add `debug` message in post-processing algorithm.
format as 
```
[T Debug] tor:%f, vis-satellite number: %d, DOP:%.3f,  obs per slips:%d,   unvis-angle:%f,  average CN0:%f,   average elevation of satellite:%f;
[T Debug] tor:%f, vis-satellite number: 50, DOP:1.105, obs per slips:1220, unvis-angle:122, average CN0:40.3, average elevation of satellite:22.33;
```

## plot the lines of indicators

To get these indicators, calculation is needed if no value in the algorithm.
![iamge](./picture/average%20CN0.png)
![iamge](./picture/hDop.png)
![iamge](./picture/pDop.png)
![iamge](./picture/average%20Elevation.png)
![iamge](./picture/cycleSlipratio.png)
![iamge](./picture/vis%20satellite%20number.png)     

## statitics analysis

## add classification analysis in QNE algorithm
:arrow_forward:`2024/2/19 ` confirm that the average elevation of valid carrier phase can be regarded as a important indicator to judge weather the vihecle is under elevated or in boulevard 


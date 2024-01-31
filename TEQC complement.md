# TEQC develop
## diagram

```mermaid
graph LR
 O[(RTCM.log)]--> A(convbin.exe) -->|RINEX 2.11 </br> obs+nav|D(teqc.exe)-->B[.yyS]
    B --> C[1.obs per slip]
 B --> R[2.average CN0]
 B --> T[3.the ratio of complete]
 B --> Y[4/multipath]  
    
```

```mermaid
%%{init: {"flowchart": {"htmlLabels": false}} }%%
flowchart TD
    markdown["`This **is** _Markdown_`"]
    newLines["Line1
    Line 2
    Line 3"]
    markdown --> newLines
```



## TEQC.exe



## Convbin code 
rinex.c 中的outrnxb主要功能是对rinex body进行输出
```rinex.c

extern int outrnxb()
{
  if (opt->rnxver <= 299 && sys == SYS_GPS)
  {
    fprintf(fp, "...");
    sep = "   ";
  }

}


```

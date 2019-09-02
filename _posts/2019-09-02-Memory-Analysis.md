---
layout: post
title: "David Collins, 4rch3r, Memory Analysis"
date: 2019-09-02
---
# Memory Analysis
##### A deep dive into memory. 
* Tools
  * Acquisition Tools
  * Analysis Tools
* Use Cases
* Walkthrough w/ samples

----

### Acquisition Tools
* Comae's DumpIt.exe
* Google Rekall's winpmem


### Analysis Tools
* Volatility
* Google Rekall
* FireEye Redline

----

### Use Cases
* Incident Response
  * Rootkit Discovery
  * "Fileless" Malware
* Threat Hunting

----

### Aquiring Memory (Local)
##### Comae's DumpIt
```
C:\DumpIt.exe /OUTPUT image.bin

  DumpIt 3.0.20180528.1
  Copyright (C) 2007 - 2017, Matthieu Suiche <http://www.msuiche.net>
  Copyright (C) 2012 - 2014, MoonSols Limited <http://www.moonsols.com>
  Copyright (C) 2015 - 2017, Comae Technologies FZE <http://www.comae.io>
  Copyright (C) 2017 - 2018, Comae Technologies DMCC <http://www.comae.io>

   Destination path:           \??\C:\Dumpit\dump.bin  

    Computer name:              Comp
    --> Proceed with the acquisition ? [y/n] y
```

####

----

### Walkthrough w/ Samples
#### Ac
#### Volatility

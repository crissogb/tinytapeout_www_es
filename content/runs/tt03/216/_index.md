---
hidden: true
title: "216 Seven Segment Clock"
weight: 217
---

## 216 : 0b 011 011 000 : Seven Segment Clock

{{< tt-scanchain-switches "011011000" >}}

* Author: Greg Davill
* Description: Logic to drive 6 external 74hct595's that in turn drive 7 segment displays. The displays form a digital clock.
* [GitHub repository](https://github.com/gregdavill/tt02-clock)
* HDL project
* [Extra docs](TBD)
* Clock: 128Hz Hz
* External hardware: 6x 74hct595's, 6x 7segment

Image path is broken

### How it works

TBD

### How to test

TBD

### IO

| # | Input        | Output       |
|---|--------------|--------------|
| 0 | clock  | sclk |
| 1 | reset  | latch |
| 2 | minute_up  | data |
| 3 | hour_up  | none |
| 4 | none  | none |
| 5 | none  | none |
| 6 | none  | none |
| 7 | none  | none |

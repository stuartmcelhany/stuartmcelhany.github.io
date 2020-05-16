---
layout: post
title: Auto Titrator
thumbnail: "/images/autotitrator/tcurve.png"
---

Non-linear optimization used to fit pH titration data.

![Titration curve data]({{ site.baseurl }}/images/autotitrator/tcurve.png)

The goal of the auto titrator is to bring the pH of any given sample to any user-entered value. Two tanks, one containing acid and one base, are dispensed via peristaltic pumps into the sample. The module is controlled by a Raspberry Pi. Due to the 5 second delay in pH monitoring, predictive methods were used. Non-linear regression was used to fit the first several data experimental data points to a inverse hyperbolic sine function (a function that somewhat resembles a titration curve).

[GitHub](https://github.com/stuartmcelhany/titrator-curve-fitting)
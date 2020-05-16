---
layout: post
title: Boiling Point Calculator
thumbnail: /images/bpcalculator/PREOS_BoilingPoint.png
---

Boiling point calculator using Peng-Robinson equation of state.

![_config.yml]({{ site.baseurl }}/images/bpcalculator/PREOS_BoilingPoint.png)

Using the Peng-Robinson equation of state, this code calculates the boiling point temperature at given pressures. The input pressure is used as the saturated pressure in the calculations. The boiling point temperature is found by equating the saturated liquid and saturated vapor fugacities, and numerically solving for the temperature via bisection method. Any fluid can be used as long as the constants are changed to the appropriate values, such as the acentric factor and critical temperature/pressure.

[GitHub](https://github.com/stuartmcelhany/boiling-point-calculator-peng-robinson)

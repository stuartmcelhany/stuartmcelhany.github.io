---
layout: post
title: Unit Cell Cloner
thumbnail: "/images/unitcellcloner/fau5_3x3x3.png"
---

Repeats a unit cell in +/- x, y, and z directions.

![Triclinic unit cell repeated in x, y, and z directions]({{ site.baseurl }}/images/unitcellcloner/fau5_3x3x3.png)

The unit cell cloner takes any .xyz file and outputs a new file with the original coordinates repeated in a specified number of dimensions. For example, the user can input a molecule - say potassium dichromate - specify the axial distances and the number of repetitions, and the program will output a lattice corresponding to the user inputs. The photos shown to the right are of faujasite. The top photo is the initial molecule and the photo below is of a 3x3x3 lattice of faujasite. This program is useful in determining stability of larger molecular structures. The output file can be used with other software such as CP2K to preform accurate density functional theory calculations.

[GitHub](https://github.com/stuartmcelhany/faujisite-unit-cell)
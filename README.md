# HoloFoodR: a statistical programming framework for holo-omics data integration workflows

This repository includes all the source files to used to generate article on
[HoloFoodR R
package](https://bioconductor.org/packages/release//bioc/html/HoloFoodR.html).
The article is based on the [OUP LaTex
Template](https://ctan.org/pkg/oup-authoring-template).

# How to compile the article

[Install](https://tug.org/texlive/) TeX Live. Ensure that the
[package](https://ctan.org/pkg/oup-authoring-template)
`oup-authoring-template` is installed.

Then run the following commands in the terminal:

```bash
pdflatex --interaction=nonstopmode main.tex
biber main
pdflatex --interaction=nonstopmode main.tex
```

You can safely ignore the warnings. The article will comply normally.

# Software versions used for compilation

To ensure full reproducibility, the output of `pdflatex --version` is below.
The compilation of this article has been tested.

```
pdfTeX 3.141592653-2.6-1.40.27 (TeX Live 2025/nixos.org)
kpathsea version 6.4.1
Copyright 2025 Han The Thanh (pdfTeX) et al.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the pdfTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the pdfTeX source.
Primary author of pdfTeX: Han The Thanh (pdfTeX) et al.
Compiled with libpng 1.6.47; using libpng 1.6.47
Compiled with zlib 1.3.1; using zlib 1.3.1
Compiled with xpdf version 4.04
```

LaTeX Package: causets
======================
This is a LaTeX package to create (Hasse) diagrams of causal sets - short causets (locally finite, partially ordered sets) to be used inline with text or mathematical expressions, as well as with TikZ pictures. 

The three main commands (macros) are 
```tex
% causet generated from a permutation:
\pcauset{..,i,..,j,..}
% causet generated from a permutation, but some links are removed:
\rcauset{..,i,..,j,..}{..,i/j,..}
% causet with events positioned by a permutation, links are specified explicitly:
\causet{..,i,..,j,..}{..,i/j,..}
```

For a full documentation, please see causets.pdf.

Additional Packages
===================
This package is built on the package `tikz`, which is usually included in the standard LaTeX installations. 

Bug Reports
===========
Problems with the package are reported here:
https://github.com/c-minz/LaTeX-causets/issues

If you find a bug, please report it by including:
* Comprehensive problem description - including error or warning messages (if any).
* Minimal test file that shows the problem.
* Used drivers/programs with version informations.
* Version information about used packages and programs.
* Please no other files than the minimal test file (*.tex).

Bug reports can be send to the maintainer:
  C. Minz
  christoph{dot}minz[AT]gmail{dot}com

Information on Distribution
===========================
Copyright 2020 by C. Minz

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License, either version 1.3 of this license or (at your option) any later version.
The latest version of this license is in
http://www.latex-project.org/lppl.txt

This work has the LPPL maintenance status "maintained".

The current maintainer of this work is C. Minz.
https://github.com/c-minz

Current version: 1.1

CTAN location: /graphics/pgf/contrib/causets/


This work consists of the files causets.sty, causets.tex, causets.pdf, causet_tikz_example1.tex, causet_tikz_example1.pdf, causet_tikz_example2.tex, causet_tikz_example2.pdf

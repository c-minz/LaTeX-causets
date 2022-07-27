# The `causets` package
The LaTeX package `causets` lets you create (Hasse) diagrams of causal sets. Causal sets (causets) are locally finite, partially ordered sets and are consider as a framework for quantum gravity. This package is built on the package `tikz`, which is usually included in the standard LaTeX installations and loaded automatically with `\usepackage{causets}`.

The diagrams can be used inline with text or mathematical expressions, or they may be included in a TikZ pictures. 
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
The documentation includes some examples.
More examples are included at
https://github.com/c-minz/LaTeX-causets/tree/main/examples

## Bug reports
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

## License and distribution
Copyright 2020-2022 by C. Minz

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License, either version 1.3 of this licence or (at your option) any later version.
The latest version of this licence is in
http://www.latex-project.org/lppl.txt

This work has the LPPL maintenance status "maintained".

The current maintainer of this work is C. Minz.
https://github.com/c-minz

**Current version: v1.3.1**

CTAN location: /graphics/pgf/contrib/causets/


This work consists of the files causets.sty, causets.tex, causets.pdf, causet_tikz_example1.tex, causet_tikz_example1.pdf, causet_tikz_example2.tex, causet_tikz_example2.pdf

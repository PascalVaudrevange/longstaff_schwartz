# longstaff_schwartz
Longstaff-Schwartz algorithm for an American put option including Roger's upper bound


This is a document written using literate programming, pweave (http://mpastell.com/pweave/) for Python.

In order to extract the code, run ptangle from the command line.

ptangle "longstaff_schwartz.pnw"

In order to recreate the document, run from within python

import pweave pweave.weave(r'longstaff_schwartz.pnw', figformat='png', doctype='texmint

followed by running LaTeX

pdflatex longstaff_schwartz.tex

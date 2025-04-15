# MasterThesisDocument

To update the nomeclature section I have to run the following commands:

pdflatex main.tex
makeindex main.nlo -s nomencl.ist -o main.nls
pdflatex main.tex
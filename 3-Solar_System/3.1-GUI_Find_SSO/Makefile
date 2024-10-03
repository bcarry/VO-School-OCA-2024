all:
	make latex
	make bibtex
	make latex
	make pdf

latex:
	pdflatex *.tex

pdf:
	mv main.pdf 3.1-GUI_Find_SSO-SkyBoT.pdf

bibtex:
	bibtex main

clean:
	rm *bbl *aux *nav *out *dvi *snm *toc *blg *log *~ sections/*~ sections/*log

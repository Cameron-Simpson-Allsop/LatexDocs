BASENAME = MastersResults

default.SILENT:
	pdflatex  ${BASENAME}.tex
	bibtex ${BASENAME}.aux
	pdflatex  ${BASENAME}.tex
	pdflatex ${BASENAME}.tex

clean:
	rm -f *.nav *.run.xml *.out *.snm *.bcf *.aux *.log *.toc *.bbl *.blg *-blx.bib


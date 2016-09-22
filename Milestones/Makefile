ROOT=M4.1

default:
	pdflatex  ${ROOT}
	biber ${ROOT}
	pdflatex ${ROOT}
	pdflatex ${ROOT}

clean:
	rm -vf *.glo
	rm -vf *.glg
	rm -vf *.gls
	rm -vf *.ist
	rm -vf *.aux
	rm -vf *.bbl
	rm -vf *.bcf
	rm -vf *.blg
	rm -vf *.log
	rm -vf *.out
	rm -vf *.run.xml

SHORT=D4.1
LONG=D4.2

default: all

all: shortpulse longpulse

shortpulse:
	pdflatex  ${SHORT}
	#makeglossaries -s ${SHORT}.ist -t ${SHORT}.glg ${SHORT}.glo
	#pdflatex  ${SHORT}
	biber ${SHORT}
	pdflatex ${SHORT}
	pdflatex ${SHORT}

longpulse:
	pdflatex  ${LONG}
	#makeglossaries -s ${LONG}.ist -t ${LONG}.glg ${LONG}.glo
	#pdflatex  ${LONG}
	biber ${LONG}
	pdflatex ${LONG}
	pdflatex ${LONG}


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
	rm -vf *.pdf
	rm -vf *.run.xml

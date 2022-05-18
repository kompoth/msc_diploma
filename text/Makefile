SOURCE=main.tex
DOCNAME=diploma

all:
	pdflatex -jobname=${DOCNAME} ${SOURCE}
	pdflatex -jobname=${DOCNAME} ${SOURCE}

clean:
	rm -f ${DOCNAME}.*

.PHONY: clean all

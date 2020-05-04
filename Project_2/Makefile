pdf: ps
	ps2pdf proj2.ps

ps:	dvi
	dvips -t a4 proj2.dvi

dvi:
	latex proj2
	pdflatex proj2

clean:
	rm -f proj2.{ps,pdf,log,aux,out,dvi,bbl,blg}

clean-trash:
	rm -f proj2.{ps,log,aux,dvi}

clean-pdf:
	rm -f proj2.pdf
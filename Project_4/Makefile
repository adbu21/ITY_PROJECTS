pdf: ps
	ps2pdf proj4.ps

ps:	dvi
	dvips proj4.dvi

dvi:
	latex proj4
	latex proj4
	bibtex proj4
	latex proj4

clean:
	rm -f proj4.{ps,pdf,log,aux,out,dvi,bbl,blg}

clean-trash:
	rm -f proj4.{ps,log,aux,dvi}

clean-pdf:
	rm -f proj4.pdf
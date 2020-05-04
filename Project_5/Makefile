pdf: ps
	ps2pdf proj5.ps

ps:	dvi
	dvips -t a4 proj5.dvi

dvi:
	latex proj5
	latex proj5

clean:
	rm -f proj5.{ps,pdf,log,aux,out,dvi,bbl,blg}

clean-trash:
	rm -f proj5.{ps,log,aux,dvi}

clean-pdf:
	rm -f proj5.pdf
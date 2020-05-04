pdf: ps
	ps2pdf -sPAPERSIZE=a4 proj3.ps

ps:	dvi
	dvips -t a4 proj3.dvi

dvi:
	latex proj3
	latex proj3

clean:
	rm -f proj3.{ps,pdf,log,aux,out,dvi,bbl,blg}

clean-trash:
	rm -f proj3.{ps,log,aux,dvi}

clean-pdf:
	rm -f proj3.pdf
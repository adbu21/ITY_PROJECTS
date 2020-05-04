pdf: ps
	ps2pdf proj1.ps

ps:	dvi
	dvips -t a4 proj1.dvi

dvi:
	latex proj1
	latex proj1

clean:
	rm -f proj1.{ps,pdf,log,aux,out,dvi,bbl,blg}

clean-trash:
	rm -f proj1.{ps,log,aux,dvi}

clean-pdf:
	rm -f proj1.pdf
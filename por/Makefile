all: cvpor clean

cvpor:
	pdflatex cvpor.tex
	bibtex cvpor
	makeindex cvpor.tex
	pdflatex cvpor.tex
	pdflatex cvpor.tex
clean:
	rm -rf cvpor.{aux,bbl,blg,ilg,ind,log,toc,out,sw[a-z],lof,lot}

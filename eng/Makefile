all: cveng clean

cveng:
	pdflatex cveng.tex
	bibtex cveng
	makeindex cveng.tex
	pdflatex cveng.tex
	pdflatex cveng.tex
clean:
	rm -rf cveng.{aux,bbl,blg,ilg,ind,log,toc,out,sw[a-z],lof,lot}

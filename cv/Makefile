fast:
	pdflatex cv.tex
	cp ./cv.pdf /Users/dekura/chen/resume/dekura.github.io/data/cv.pdf

all:
	pdflatex cv.tex
	biber cv
	pdflatex cv.tex
	pdflatex cv.tex
	cp ./cv.pdf /Users/dekura/chen/resume/dekura.github.io/data/cv.pdf

clean:
	rm *.log *.aux *.blg *.bbl *.gz *.dvi *.thm *.dat *.out

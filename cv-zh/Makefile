fast:
	xelatex cv_zh.tex

all:
	xelatex cv_zh.tex
	biber cv_zh
	xelatex cv_zh.tex
	xelatex cv_zh.tex
#	cp ./cv.pdf /Users/dekura/chen/resume/dekura.github.io/data/cv.pdf

clean:
	rm *.log *.aux *.blg *.bbl *.gz *.dvi *.thm *.dat *.out

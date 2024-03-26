.POSIX:
.SUFFIXES:
PDFLATEX = pdflatex

all: resume.pdf cv.pdf
clean:
	rm -f *.log *.aux *.pdf

.SUFFIXES: .tex .pdf
.tex.pdf:
	$(PDFLATEX) $<

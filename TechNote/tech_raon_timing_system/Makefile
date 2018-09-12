TARGET=tech_timing


.PHONY: all clean


all: *.tex
	latex $(TARGET).tex
	latex $(TARGET).tex
	dvipdf $(TARGET).dvi
	xpdf $(TARGET).pdf


clean: 
	rm *.aux *.dvi *.log *.pdf *.out

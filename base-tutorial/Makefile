TEX = pdflatex --interaction=nonstopmode
BIBTEX = bibtex

TARGET ?= base-tutorial

PHONY += default
default: $(TARGET).pdf

$(TARGET).pdf: $(TARGET).tex
	$(TEX) $<
	#$(BIBTEX) $(TARGET).aux
	#$(TEX) $<
	#$(TEX) $<

PHONY += run
open o: $(TARGET).pdf
	open $(TARGET).pdf

PHONY += clean
clean:
	rm -rf $(TARGET).pdf $(TARGET).out *.aux *.log *.bbl *.blg

.PHONY: $(PHONY)

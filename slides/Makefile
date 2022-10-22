DOCNAME=mcca-slides
SRC=$(DOCNAME).tex Makefile
TEXC=latex

$(DOCNAME).pdf: $(DOCNAME).ps
	ps2pdf $^
$(DOCNAME).ps: $(DOCNAME).dvi
	dvips $^
$(DOCNAME).dvi: $(SRC)
	$(TEXC) $^
	$(TEXC) $^
clean:
	rm -f \
$(DOCNAME).aux \
$(DOCNAME).dvi \
$(DOCNAME).log \
$(DOCNAME).nav \
$(DOCNAME).out \
$(DOCNAME).snm \
$(DOCNAME).toc \
$(DOCNAME).dvi \
$(DOCNAME).pdf \
$(DOCNAME).ps \
$(DOCNAME).vrb \
texput.log \

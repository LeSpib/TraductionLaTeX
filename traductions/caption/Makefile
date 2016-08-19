# Variables pour le codage 
latex = pdflatex
doc = caption-fr

# Déclaration des actions (et dépendances) 
all: $(doc).pdf

$(doc).pdf: $(doc).tex
	$(latex) $(doc).tex
	$(latex) $(doc).tex
	$(latex) $(doc).tex

# Nettoyage simple du répertoire
clean:
	rm -f  \
		$(doc).aux \
		$(doc).bbl \
		$(doc).blg \
		$(doc).cfg \
		$(doc).glo \
		$(doc).gls \
		$(doc).hd \
		$(doc).idx \
		$(doc).ind \
		$(doc).ilg \
		$(doc).lof \
		$(doc).log \
		$(doc).lot \
		$(doc).out \
		$(doc).toc \
                cat-eps-converted-to.pdf


# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

# Variables pour le codage 
latex = pdflatex
doc = thmbox-fr

# Déclaration des actions (et dépendances) 
all: $(doc).pdf

$(doc).pdf: $(doc).dtx
	$(latex) $(doc).dtx
	$(latex) $(doc).dtx
	$(latex) $(doc).dtx

# Nettoyage simple du répertoire
clean:
	rm -f  \
		$(doc).aux \
		$(doc).bbl \
		$(doc).blg \
		$(doc).cfg \
		$(doc).glo \
		$(doc).gls \
		$(doc).idx \
		$(doc).ind \
		$(doc).ilg \
		$(doc).lof \
		$(doc).log \
		$(doc).lot \
		$(doc).out \
		$(doc).toc

# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

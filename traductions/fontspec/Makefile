# Variables pour le codage 
latex = xelatex
doc = fontspec-fr

# Déclaration des actions (et dépendance) 
all: $(doc).pdf

$(doc).pdf: $(doc).dtx
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
		$(doc).idx \
		$(doc).ind \
		$(doc).ilg \
		$(doc).lof \
		$(doc).log \
		$(doc).lot \
		$(doc).out \
		$(doc).toc \
                fontspec-style-fr.sty

# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

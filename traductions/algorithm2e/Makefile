# Variables pour le codage 
latex = pdflatex
doc = algorithm2e-fr

# Déclaration des actions (et dépendances) 
all: $(doc).pdf

$(doc).pdf: $(doc).tex
	$(latex) $(doc).tex
	$(latex) $(doc).tex
	makeindex -o $(doc).ind $(doc).idx
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
		$(doc).idx \
		$(doc).ind \
		$(doc).ilg \
		$(doc).loa \
		$(doc).lof \
		$(doc).log \
		$(doc).lot \
		$(doc).out \
		$(doc).toc

# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

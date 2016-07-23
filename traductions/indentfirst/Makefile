# Variables pour le codage 
latex = pdflatex
doc = indentfirst-fr

# Déclaration des actions (et dépendance) 
all: $(doc).pdf

$(doc).pdf: $(doc).dtx
	$(latex) $(doc).dtx

# Nettoyage simple du répertoire
clean:
	rm -f  \
		$(doc).aux \
		$(doc).bbl \
		$(doc).blg \
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

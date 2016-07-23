# Variables pour le codage 
latex = pdflatex
doc = array-fr
styleind = gind-fr
styleglo = gglo-fr

# Déclaration des actions (et dépendances) 
all: $(doc).pdf

$(doc).pdf: $(doc).dtx
	$(latex) $(doc).dtx
	$(latex) $(doc).dtx
	makeindex -s $(styleind).ist -o $(doc).ind $(doc).idx
	makeindex -s $(styleglo).ist -o $(doc).gls $(doc).glo
	$(latex) $(doc).dtx
	$(latex) $(doc).dtx

# Nettoyage simple du répertoire
clean:
	rm -f  \
		$(doc).out \
		$(doc).lof \
		$(doc).log \
		$(doc).lot \
		$(doc).idx \
		$(doc).ind \
		$(doc).ilg \
		$(doc).toc \
		$(doc).bbl \
		$(doc).blg \
		$(doc).aux 

# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

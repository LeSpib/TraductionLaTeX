# Variables pour le codage 
latex = pdflatex
doc = datatool-user-fr
styleglo = gglo-fr
styleind = gind-fr

# Déclaration des actions (et dépendances) 
all: $(doc).pdf

$(doc).pdf: $(doc).tex
	$(latex) $(doc).tex
	$(latex) $(doc).tex
	makeindex -s $(styleind).ist -o $(doc).ind $(doc).idx
	makeindex -s $(styleglo).ist -o $(doc).gls $(doc).glo
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
		$(doc).loe \
		$(doc).lof \
		$(doc).log \
		$(doc).lot \
		$(doc).out \
		$(doc).toc

# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

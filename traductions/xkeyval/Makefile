# Variables pour le codage 
latex = xelatex
doc = xkeyval-fr
styleglo = gglo-fr
styleind = gind-fr

# Déclaration des actions (et dépendance) 
all: $(doc).pdf

$(doc).pdf: $(doc).dtx
	$(latex) $(doc).dtx
	$(latex) $(doc).dtx
	bibtex $(doc).aux
	makeindex -s $(styleind).ist -o $(doc).ind $(doc).idx
	makeindex -s $(styleglo).ist -o $(doc).gls $(doc).glo
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
		$(doc).toc \
		xkvpream.ble \
		xkeyval.bib

# Nettoyage complet
mrproper: clean
	rm -f $(doc).pdf

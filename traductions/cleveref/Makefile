# Variables pour le codage 
latex = xelatex
doc = cleveref-fr
styleglo = gglo-fr
styleind = gind-fr

# Déclaration des actions (et dépendance) 
all: $(doc).pdf

$(doc).pdf: $(doc).dtx
	$(latex) "\AtBeginDocument{\OnlyDescription} \input $(doc).dtx"
	$(latex) "\AtBeginDocument{\OnlyDescription} \input $(doc).dtx"
	makeindex -s $(styleind).ist -o $(doc).ind $(doc).idx
	makeindex -s $(styleglo).ist -o $(doc).gls $(doc).glo
	$(latex) "\AtBeginDocument{\OnlyDescription} \input $(doc).dtx"
	$(latex) "\AtBeginDocument{\OnlyDescription} \input $(doc).dtx"


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

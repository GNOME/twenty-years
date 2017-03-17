SOURCES =					\
	glossary-entries.tex			\
	historybit.tex				\
	intro.tex				\
	main.tex
#	references.bib

# BIB_GENERATED = references_bibertool.bib

main.pdf: $(SOURCES) $(BIB_GENERATED)
	xelatex main
#	biber main.bcf
	makeglossaries main
	makeindex main
	xelatex main

#references_bibertool.bib: references.bib $(SOURCES)
#	biber --tool references.bib

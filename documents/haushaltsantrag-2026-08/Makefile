SOURCE=haushaltsantrag-2026-08

make:
	pdflatex $(SOURCE).tex -output-format=pdf
	pdflatex $(SOURCE).tex -output-format=pdf  # zweiter Lauf: Seitenverweise, Titelband
	make clean

clean:
	rm -rf  $(TARGET) *.class *.html *.log *.aux *.out

TARGET=Set_2.pdf
all: ${TARGET}
%.pdf: %.tex
	xelatex -shell-escape $<
clean:
	rm ${TARGET}

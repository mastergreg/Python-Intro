TARGET=Set_1.pdf
all: ${TARGET}
%.pdf: %.tex
	xelatex -shell-escape $<
clean:
	rm ${TARGET}

sources=$(wildcard *.dot)
all: $(sources:.dot=.png)

%.png: %.dot
	dot -Tpng $< -o $@

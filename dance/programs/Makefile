allhtml: $(shell find . -name "*.rst" | sed 's/rst/html/')

%.html: %.rst
	rst2html --stylesheet-path=dances.css $< > $@

allhtml: $(shell find . -name "*.rst" | sed 's/rst/html/')

%.html: %.rst
	rst2html5 --stylesheet=dances.css $< > $@

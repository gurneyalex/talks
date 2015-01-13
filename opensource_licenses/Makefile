all : html

pdf : opensource_licenses.pdf

html : opensource_licenses.html

%.html : %.rst
	landslide -t light -r -d $@ $<

%.pdf : %.rst
	landslide -t light -r -d $@ $<

clean:
	rm -f opensource_licenses.html opensource_licenses.pdf

.PHONY : all html pdf clean

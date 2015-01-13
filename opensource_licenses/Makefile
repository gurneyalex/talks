OPTIONS=--theme small-white --current-slide

all : html

html : opensource_licenses.html

%.html : %.rst
	rst2s5 ${OPTIONS} $< $@

clean:
	rm -f opensource_licenses.html 

.PHONY : all html pdf clean

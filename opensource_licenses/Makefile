all : html

html : opensource_licenses.html

%.html : %.rst
	rst2s5 --theme small-black $< $@

clean:
	rm -f opensource_licenses.html 

.PHONY : all html pdf clean

all: millis

millis: millis.c
	gcc millis.c -o millis

clean: 
	rm millis

install: all
	@mkdir "${HOME}/.bin" 2>/dev/null;	\
		cp ./millis "${HOME}/.bin/"

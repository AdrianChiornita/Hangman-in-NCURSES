build: hangman

hangman: hangman.o
	gcc hangman.o -o hangman -lcurses

hangman.o: hangman.c
	gcc -Wall -g -c hangman.c

clean: hangman hangman.o
	rm hangman hangman.o

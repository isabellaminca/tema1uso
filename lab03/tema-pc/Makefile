all: tema

tema: tema.o utils.o
	gcc -Wall tema.o utils.o -o tema

tema.o: tema.c
	gcc -Wall -c tema.c

utils.o: utils.c
	gcc -Wall -c utils.c

run: tema
	./tema

clean:
	rm -f *.o *~ tema

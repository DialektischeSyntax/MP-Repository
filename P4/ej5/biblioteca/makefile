#Makefile para crear las bibliotecas de la práctica 4
CFLAGS = -c -g -ansi -Wall

bib: pilas.a colas.a

colas.a: colas.o
	ar -rsv colas.a colas.o
	
pilas.a: pilas.o
	ar -rsv pilas.a pilas.o

pilas.o: pilas.c pilas.h
	gcc $(CFLAGS) pilas.c

colas.o: colas.c colas.h
	gcc $(CFLAGS) colas.c

clean:
	rm -f *.o 



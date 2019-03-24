CC = g++ -c

calc:	add.o sub.o mul.o div.o main.o
	g++ add.o sub.o mul.o div.o main.o -o calc

add.o:	add.cpp
	$(CC) add.cpp

sub.o:	sub.cpp
	$(CC) sub.cpp

mul.o:	mul.cpp
	$(CC) mul.cpp

div.o:	div.cpp
	$(CC) div.cpp

main.o: main.cpp
	$(CC) main.cpp

clean: 
	rm -f calc *.o

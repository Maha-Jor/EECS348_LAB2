
CC= gcc

CFLAGS= -c -Wall

OBJECTS = main.o isEven.o isOdd.o

all: prog

prog:$(OBJECTS)
	$(CC) $(OBJECTS) -o prog

main.o: main.c
	$(CC) $(CFLAGS) main.c

isEven.o: isEven.c
	$(CC) $(CFLAGS) isEven.c

isOdd.o: isOdd.c
	$(CC) $(CFLAGS) isOdd.c

%.o: %.c
	$(CC) $(CFLAGS) $<

clean: 
	rm -rf *.o

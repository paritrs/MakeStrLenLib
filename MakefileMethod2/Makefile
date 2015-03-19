CC=g++

CFLAGS=-c -Wall

all: main

main: mainfunc.o func.o
	$(CC) mainfunc.o func.o -o main

mainfunc.o: mainfunc.cpp
	$(CC) $(CFLAGS) mainfunc.cpp

func.o: func.cpp
	$(CC) $(CFLAGS) func.cpp

clean:
	rm *o main

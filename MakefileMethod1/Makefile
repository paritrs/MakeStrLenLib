all: main
	
main: mainfunc.o func.o
	g++ mainfunc.cpp func.cpp -o main

mainfunc.o: mainfunc.cpp
	g++ -c mainfunc.cpp

func.o: func.cpp
	g++ -c func.cpp

clean:
	rm *o main

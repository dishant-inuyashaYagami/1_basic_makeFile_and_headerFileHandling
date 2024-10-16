all: exe.out
	./exe.out

exe.out: main.o class.o
	g++ main.o class.o -o exe.out

main.o: main.cpp class.h
	g++ -c main.cpp

class.o: class.h class.cpp
	g++ -c class.cpp 

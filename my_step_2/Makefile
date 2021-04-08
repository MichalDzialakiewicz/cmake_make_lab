rect: main.o polygon.o rectangle.o triangle.o
	g++ main.o polygon.o rectangle.o triangle.o -o rect

main.o: main.cpp polygon.h rectangle.h triangle.h
	g++ -o main.o -c main.cpp

polygon.o: polygon.cpp polygon.h
	g++ -o polygon.o -c polygon.cpp

rectangle.o:
	g++ -o rectangle.o -c rectangle.cpp

triangle.o:
	g++ -o triangle.o -c triangle.cpp

all: amazon

amazon: main

main: main.o
	g++ main.o -o main -lpqxx -lpq

main.o: main.cpp
	g++ -c main.cpp --std=c++14 -g

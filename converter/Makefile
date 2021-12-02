CXX:=g++
CXXFLAGS:=$(shell root-config --cflags) $(shell root-config --libs) -O3 -march=native -std=c++17
INCLUDE:=converter.h hardcoded.h

readerfast: converter.cpp
	$(CXX) converter.cpp $(CXXFLAGS) -o dataconverter

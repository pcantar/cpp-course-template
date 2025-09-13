# Simple Makefile for C++ build
CXX = g++
CXXFLAGS = -std=c++17 -Wall -Wextra
TARGET = main

all: $(TARGET)

$(TARGET): main.cpp
	$(CXX) $(CXXFLAGS) -o $(TARGET) main.cpp

clean:
	rm -f $(TARGET)

TARGET = myserver myclient

CC = gcc
C++ = g++
CFLAGS = -Wall

all:$(TARGET)

server:myserver.cpp
	$(C++) $(CFLAGS) -o $@ $<

client:myclient.cpp
	$(C++) $(CFLAGS) -o $@ $<

clean:
	rm -rf $(TARGET)


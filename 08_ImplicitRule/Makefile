.PHONY: hello

CC := gcc
CFLAGS := -I.

INC_FILE := hello.h

hello: main.o hello.o
	$(CC) -o $@ $^ $(CFLAGS)

clean: 
	rm hello *.o


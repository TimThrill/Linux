# variableName = value
# gcc
CC = gcc
CFLAGS = -Wall -O -g
OBJECTS = hello.so

# target : prerequisites
# TAB SPACE command
hello.so :
	$(CC) -fPIC -shared $(CFLAGS) -o hello.so hello.c

.PHONY : clean
clean :
	-rm $(OBJECTS)

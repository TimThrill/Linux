# varaible name = value
# gcc
CC = gcc
CFLAGS = -Wall -fPIC -shared
OBJECTS = hello.so

# target : prerequisites
hello.so :
	$(CC) $(CFLAGS) -o hello.so hello.c

.PHONY : clean
clean :
	-rm $(OBJECTS)

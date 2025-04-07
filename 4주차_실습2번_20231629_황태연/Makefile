cc = gcc
target = animal.exe
objects = dog.o blackcow.o turtle.o main.o

$(target): $(objects)
	$(CC) -o $(target) $(objects)
$(objects) : animal.h

.PHONY: clean
clean:
	rm $(target) $(objects)

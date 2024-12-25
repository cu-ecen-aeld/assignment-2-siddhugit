CC=$(CROSS_COMPILE)gcc

all: writer_build

writer_build: writer.o
	$(CC) -o writer writer.o

%.o: %.c 
	$(CC) -c -o $@ $<

clean:
	rm -rf *.o
	rm -rf writer
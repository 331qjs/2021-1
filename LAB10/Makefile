all: test

test: main.o read.o write.o
	gcc -o test main.o read.o write.o

main.o: main.c
	gcc -c main.c

read.o: read.c
	gcc -c read.c

write.o: write.c
	gcc -c write.c

clean:
	rm *.o test

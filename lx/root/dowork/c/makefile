helloWorld: helloWorld.o main.o
	gcc -o helloWorld helloWorld.o main.o

helloWorld.o: helloWorld.c
	gcc -c helloWorld.c

main.o: main.c
	gcc -c main.c

clean:
	rm -f helloWorld *.o

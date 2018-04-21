all: toy_printf

toy_printf:  toy_printf.o main[1].o
	gcc -g -Wall -o toy_printf toy_printf.o main[1].o

toy_printf.o: toy_printf.c
	gcc -g -Wall -c -o toy_printf.o toy_printf.c
	
main[1].o: main[1].c
	gcc -g -Wall -c -o main[1].o main[1].c

clean:
	rm -f *.o
 

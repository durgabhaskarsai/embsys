main: main.o add.o sub.o
	gcc -o main main.o add.o sub.o

main.o:main.c
	gcc  -o main.o main.c -c
add.o:add.c
	gcc  -o add.o add.c -c
sub.o: sub.c
	gcc -o sub.o sub.c -c
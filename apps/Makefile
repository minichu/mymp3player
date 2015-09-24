.PHONY: all clean

player : player.c
	gcc -g -c -I /home/minichu/150923_make/3/include player.c -o player.o
	gcc -o player -L /home/minichu/150923_make/3/lib player.o -lfuncs
clean:
	rm -f player.o player

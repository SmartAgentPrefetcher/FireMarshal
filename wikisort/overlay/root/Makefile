CC = riscv64-unknown-linux-gnu-gcc
CFLAGS := -O3 -static

wikisort: WikiSort.c
	$(CC) $(CFLAGS) -o wikisort WikiSort.c -lm

clean:
	rm -f wikisort

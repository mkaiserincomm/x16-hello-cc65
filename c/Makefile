ALL_C = $(wildcard *.c) $(wildcard *.h)

all: $(ALL_C)
	cl65 -t cx16 -o HELLOC.PRG -l hello.list hello.c
	cp HELLOC.PRG "/mnt/c/Users/mkaiser/OneDrive - InComm/Downloads/x16emu_win-r38"

clean:
	rm -f *.PRG *.list *.o
	rm "/mnt/c/Users/mkaiser/OneDrive - InComm/Downloads/x16emu_win-r38/HELLOC.PRG"

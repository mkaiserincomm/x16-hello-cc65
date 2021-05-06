ALL_ASM = $(wildcard *.asm) $(wildcard *.inc)

all: $(ALL_ASM)
	cl65 -t cx16 -o HELLOASM.PRG -l hello.list hello.asm 
	cp HELLOASM.PRG "/mnt/c/Users/mkaiser/OneDrive - InComm/Downloads/x16emu_win-r38"
clean:
	rm -f *.PRG *.list *.o
	rm "/mnt/c/Users/mkaiser/OneDrive - InComm/Downloads/x16emu_win-r38/HELLOASM.PRG"
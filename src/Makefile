#Author Pedro Expedito De Oliveira
#Date: 21/10/2020

BIN="../bin"
CC="gcc"
CCW="x86_64-w64-mingw32-gcc"

all:
	${CC} -g -Wall -Wextra main.c -o ${BIN}/runme.elf
windows:
	${CCW} -Wall -Wextra main.c -o ${BIN}/runme.exe
run:
	${BIN}/runme.elf
RunWindows:
	wine64-stable ${BIN}/runme.exe
clear:
	rm -r -f ${BIN}/*


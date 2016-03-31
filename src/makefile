ifeq ($(shell uname -s), Darwin)
	CC = clang
else
	CC = gcc
	CFLAGS += -pthread -lm
endif

CFLAGS += -Ofast -std=c99

all: scwe.c
	${CC} scwe.c ${CFLAGS} -o scwe

#
# tests Makefile
#

CFLAGS = -Wall -g
LDLIBS = -lrt

all: endian struct_bit tcp_new_sock measure_time stack_grow badfd platform

endian: endian.o

struct_bit: struct_bit.o

tcp_new_sock: tcp_new_sock.o

measure_time: measure_time.o

stack_grow: stack_grow.o

badfd: badfd.o

platform: platform.o

.PHONY: clean

clean:
	-rm -f endian struct_bit tcp_new_sock measure_time stack_grow badfd platform *~ *.o

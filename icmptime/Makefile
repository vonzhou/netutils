CC	= gcc
CFLAGS	= 


PROGS =	icmptime
OBJS = icmptime.o

all:	${PROGS}

icmptime:	${OBJS}
		${CC} ${CFLAGS} -o $@ ${OBJS} 

clean:
		rm -f ${PROGS} core core.* *.o temp.* *.out typescript*

CC	= gcc
CFLAGS	= 


PROGS =	myping
OBJS = myping.o

all:	${PROGS}

icmptime:	${OBJS}
		${CC} ${CFLAGS} -o $@ ${OBJS} 

clean:
		rm -f ${PROGS} core core.* *.o temp.* *.out typescript*

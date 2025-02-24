CC = gcc
CFLAGS = -Wall -Werror -g

OBJS = main.o addition.o subtraction.o multiplication.o division.o

all: calculator

calculator: $(OBJS)
	$(CC) $(CFLAGS) -o calculator $(OBJS)

%.o: %.c
	$(CC) $(CFLAGS) -c $<

clean:
	rm -f $(OBJS) calculator


CFLAGS=-Wall #-Werror

all: ot290-gsmtap

ot290-gsmtap: main.o
	$(CC) $(LDFLAGS) -o $@ $^

%.o: %.c
	$(CC) $(CFLAGS) -o $@ -c $^

clean:
	@rm -f ot290-gsmtap *.o


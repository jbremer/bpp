OBJS:=main.o ini.o
CFLAGS:=-ggdb -std=gnu99 -I../bppsource -I../common
LDFLAGS:=-L../bppsource -lbppsource

blocksend: $(OBJS)
	$(CC) -o $@ $^ $(LDFLAGS)

.PHONY: clean
clean: 
	rm -f $(OBJS) blocksend

CC = gcc
CFLAGS = -O -Wall
MODULE = grib2_dec
OBJS = sample_decode.h prr_template.h pmf_template.h

.c.o : $(HEADER)
	$(CC) $(CFLAGS) -c $< -0 $@

$(MODULE) : $(OBJS)
	$(CC) $(OBJS) -o $(MODULE)

clean :
	rm $(OBJS) $(MODULE)
asm=$(CURDIR)/../bin/asm
acse=$(CURDIR)/../bin/acse
export asm acse
dirs:=arrays sum dowhile mult_table power semi assign arrays arrays2 misc

test :
	for i in $(dirs); do $(MAKE) -C $$i -f ../Makefile.test ; done

.PHONY : test clean

clean :
	for i in $(dirs); do $(MAKE) -C $$i -f ../Makefile.test clean ; done

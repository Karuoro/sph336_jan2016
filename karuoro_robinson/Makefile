objects= calc tempcalc test

build: $(objects)

calc:calc.cc calc.h
	g++ calc.cc -o calc
	./calc

tempcalc:tempcalc.cc tempcalc.h
	g++ tempcalc.cc -o tempcalc
	./tempcalc

test:test.cc
	g++ test.cc -o test1
	./test1

.PHONY: build calc tempcalc test1

clean:	rm *~
	rm *.o
	rm test1	
	rm tempcalc	
    rm calc    



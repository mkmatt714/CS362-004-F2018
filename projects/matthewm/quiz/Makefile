CFLAGS= -Wall -fpic -coverage -lm -std=c99

testme: testme.c
	gcc -o testme testme.c -g -coverage -fpic -lm $(CFLAGS)
	./testme &> quiztestresult.out
	gcov testme.c >> quiztestresult.out
	cat testme.c.gcov >> quiztestresult.out




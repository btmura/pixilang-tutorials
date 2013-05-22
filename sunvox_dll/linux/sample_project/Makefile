all:
	cp ../lib_x86/sunvox.so ./
	cp ../../songs/test.sunvox ./
	gcc -m32 -g -c test1.cpp
	gcc -m32 -g -c test2.cpp
	gcc -m32 -lstdc++ -ldl -lm -o test1 test1.o
	gcc -m32 -lstdc++ -ldl -lm -o test2 test2.o

clean:
	rm -f *.o *.so test1 test2 *.sunvox
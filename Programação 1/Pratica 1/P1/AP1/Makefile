hello: bin/hello.o
	gcc -o $@ $^
bin/hello.o: hello.c | bin
	gcc -c -o $@ $^
bin:
	mkdir $@
clean:
	rm -rf hello bin
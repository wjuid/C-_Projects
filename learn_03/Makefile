objects := learn.o
learn:$(objects)
	clang++ -o learn $(objects) --target=x86_64-w64-mingw

.PHONY: clean
clean:
	rm learn $(objects)
cc = clang++
objects := learn.o
learn:$(objects)
	$(cc) -o learn $(objects) --target=x86_64-w64-mingw

.PHONY: clean
clean:
	rm learn $(objects)
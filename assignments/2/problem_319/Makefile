GCC         = gcc
EXE	    = zombie
OBJ	    = zombie.o
SOURCE      = zombie.c

default: $(EXE)

$(OBJ): $(SOURCE)
	$(GCC) -c -o $@ $(SOURCE) -std=gnu99 -lrt

$(EXE): $(OBJ)
	$(GCC) $(OBJ) -o $(EXE) -std=gnu99 -lrt

clean:
	rm -rf *.o $(EXE)

.SUFFIXES: .o .c
.c.o:
	$(CC) -c $(CFLAGS) $<

CC = gcc
CFLAGS = -Wall  -Wextra -Wformat -Werror -g -O3 -std=c99 -g
SRC = ConstruccionDestruccion.c JonSnow.h
OBJ = ConstruccionDestruccion.o Ordenacion.o VerticesFunc.o InfoGrafo.o Coloreo.o AyNuestrasBonitasFunciones.o

all: $(OBJ)
	$(CC) $(CFLAGS) -o Greedy $(OBJ)

clean:
	$(RM) $(OBJ) Greedy

ConstrucciónDestrucción.o: ConstruccionDestruccion.c JonSnow.h
Ordenacion.o: Ordenacion.c JonSnow.h
VerticesFunc.o: VerticesFunc.c JonSnow.h
InfoGrafo.o: InfoGrafo.c JonSnow.h
Coloreo.o: Coloreo.c JonSnow.h
AyNuestrasBonitasFunciones.o: AyNuestrasBonitasFunciones.c JonSnow.h
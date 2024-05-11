compiler_c := gcc

hello_world:\
hello_world.o
	${compiler_c} ${^} -o ${@}

hello_world.o:\
hello_world.c
	${compiler_c} -c ${^}

compiler_c := gcc

helloworld:\
hello_world.o
	${compiler_c} ${^} -o ${@}

hello_world.o:\
hello_world.c
	${compiler_c} -c ${^}

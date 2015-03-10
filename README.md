# arm-mame
mame para linux para armv7 y opengl es 2.0

para compilarlo en linux en armv7 hay que correr en consola:
./configure CFLAGS="-O2 -march=armv7 -mfpu=vfpv3"
pudiendo cambiar esos flags segun nuestra conveniencia

luego de eso se genera el makefile, hay que escribir en consola:
make

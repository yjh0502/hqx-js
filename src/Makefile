all:
	JAVA_HEAP_SIZE=4096m emcc -O2 hq2x.c hq3x.c hq4x.c init.c -s EXPORTED_FUNCTIONS="['_hq4x_32', '_hq3x_32', '_hq2x_32', '_hqxInit', '_malloc', '_free', '_main']" -o hqx.js

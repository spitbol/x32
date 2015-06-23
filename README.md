# x32
SPITBOL x32 is the implemtation of Macro SPITBOL for 32-bit Unix. It has been developed on Linux, and should run on most other
Unix variants available for the x86 architecture.

The distribution includes a statically linked binary ./bin/spitbol that can be used directly. It is also needed to build
SPITBOL.

By default, the system is built using the gcc C compiler and the nasm assembler.

```
	make
```

It can also be built using Patrice Bellard's tiny C compiler, tcc, and the musl library:

```
	make -f Makefile-tcc
```

The source files for musl, nasm and tcc can be found in the directory ./tools. If your unix system does not incude binaries
for these tools, they can be build from the source in the ./tools directory using gcc. Just unpack the tarballs and follow
te instructions to build and install, as described in INSTALL or README, as appropriate.










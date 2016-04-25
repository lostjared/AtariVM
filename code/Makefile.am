AM_CFLAGS = -O2 $(LIBSDL_CFLAGS)  -I$(top_srcdir)/include -I$(prefix)/include 
AM_LDFLAGS = $(LIBSDL_LIBS)
bin_PROGRAMS=AtariVM AtarVM_BOOT
AtariVM_SOURCES=icode.c lex.c main.c mxfont.c parse.c pixelbuffer.c stack.c symtab.c
AtarVM_BOOT_SOURCES=ats-eboot.c

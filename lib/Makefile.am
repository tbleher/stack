noinst_LTLIBRARIES = liblgl.la libboolector.la

liblgl_la_SOURCES  = lingeling/lglib.c
liblgl_la_CPPFLAGS = -DNLGLOG -DNDEBUG -DNCHKSOL -DNLGLPICOSAT

libboolector_la_SOURCES  = boolector/boolector.c \
	boolector/btoraig.c   boolector/btoraigvec.c boolector/btorbtor.c \
	boolector/btorconst.c boolector/btorexp.c    boolector/btorhash.c \
	boolector/btormain.c  boolector/btormem.c    boolector/btorrewrite.c \
	boolector/btorsat.c   boolector/btorsmt.c    boolector/btorsmt2.c \
	boolector/btorutil.c
libboolector_la_CPPFLAGS = -DNDEBUG -DBTOR_USE_LINGELING
libboolector_la_LIBADD   = liblgl.la

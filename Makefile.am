AM_CPPFLAGS = -I$(top_srcdir)/include \
	-I$(top_builddir)/include

ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = apg apgd apgbfm

common_apg_sources = \
        bloom.c \
        sha/sha.c \
        cast/cast.c \
        rnd.c \
        pronpass.c \
        randpass.c \
        restrict.c \
        errors.c \
        apg.c \
        getopt.c \
        convert.c

apg_SOURCES = $(common_apg_sources)

apgd_SOURCES = $(common_apg_sources)
apgd_CPPFLAGS = -DCLISERV

apgbfm_SOURCES = apgbfm.c bloom.c sha/sha.c errors.c getopt.c convert.c
apgbfm_CPPFLAGS = -DAPGBFM


AM_CFLAGS = -std=c11 -Wall -fvisibility=hidden -I$(top_srcdir)/include -I$(top_srcdir)/simde

lib_LTLIBRARIES = libturbofec.la

libturbofec_la_SOURCES = \
	conv_dec.c \
	conv_enc.c \
	conv_rate_match.c \
	turbo_dec.c \
	turbo_enc.c \
	turbo_rate_match.c

noinst_HEADERS = \
	conv_gen.h \
	conv_sse.h \
	turbo_int.h \
	turbo_sse.h

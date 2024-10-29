#
#  Makefile.am
#
#  Copyright © 2020-2024 by Blockchain Commons, LLC
#  Licensed under the "BSD-2-Clause Plus Patent License"
#

lib_LTLIBRARIES = libbc-ur.la

libbc_ur_la_SOURCES = \
	bytewords.cpp \
	crc32.c \
	fountain-decoder.cpp \
	fountain-encoder.cpp \
	fountain-utils.cpp \
	memzero.c \
	random-sampler.cpp \
	sha2.c \
	ur.cpp \
	ur-decoder.cpp \
	ur-encoder.cpp \
	utils.cpp \
	xoshiro256.cpp

pkginclude_HEADERS = \
	bc-ur.hpp \
	bytewords.hpp \
	cbor-lite.hpp \
	crc32.h \
	fountain-decoder.hpp \
	fountain-encoder.hpp \
	fountain-utils.hpp \
	random-sampler.hpp \
	ur.hpp \
	ur-encoder.hpp \
	ur-decoder.hpp \
	utils.hpp \
	xoshiro256.hpp

.PHONY: lint
lint:
	cppcheck --enable=all --inline-suppr --suppress=unusedFunction --error-exitcode=1 --suppress=missingInclude .

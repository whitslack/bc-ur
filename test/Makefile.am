#
#  Makefile.am
#
#  Copyright © 2020-2024 by Blockchain Commons, LLC
#  Licensed under the "BSD-2-Clause Plus Patent License"
#

check_PROGRAMS = test

test_SOURCES = test.cpp test-utils.cpp test-utils.hpp
test_LDADD = ../src/libbc-ur.la @WS2_32_LIB@

TESTS = $(check_PROGRAMS)
noinst_PROGRAMS = $(check_PROGRAMS)

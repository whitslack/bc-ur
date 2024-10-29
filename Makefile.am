#
#  Makefile.am
#
#  Copyright © 2020-2024 by Blockchain Commons, LLC
#  Licensed under the "BSD-2-Clause Plus Patent License"
#

dist_doc_DATA = \
	LICENSE \
	README.md

dist_noinst_SCRIPTS = \
	bootstrap.sh

EXTRA_DIST = \
	CLA.md $(wildcard CLA-signed/*) \
	CODEOWNERS \
	CONTRIBUTING.md

pkgconfig_DATA = libbc-ur.pc

SUBDIRS = src test

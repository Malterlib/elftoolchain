# $Id$
#
# TET-based test suites used by the Elftoolchain project.
#

TOP=		../..

# Build TET and LIBTEST first.
SUBDIR+=	tet

# Build tests for libraries.
SUBDIR+=	libelf
SUBDIR+=	libelftc
SUBDIR+=	libdwarf

# Build tests for tools.
SUBDIR+=	elfdump
SUBDIR+=	nm

.if !make(install)
.include "$(TOP)/mk/elftoolchain.subdir.mk"
.else
install:	.SILENT .PHONY
	echo Nothing to install.
.endif

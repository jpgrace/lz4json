# Init
AC_INIT([lz4jsoncat], [3.0])
AC_CONFIG_SRCDIR([lz4jsoncat.c])
AM_INIT_AUTOMAKE
AM_CONFIG_HEADER(config.h:config.in)
AC_PROG_CC
AC_HEADER_STDC

# Shopping List
PKG_PROG_PKG_CONFIG

# Libraries
PKG_CHECK_MODULES([LZ4JSONCAT], [
  liblz4
])

# Output
AC_OUTPUT(Makefile)

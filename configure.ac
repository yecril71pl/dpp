#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.
AC_PREREQ([2.69])
AC_INIT([dpp], [0], [giecrilj@stegny.2a.pl])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_CONFIG_SRCDIR([smallpt.cpp])
AC_CONFIG_HEADERS([config.h])
# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
# Checks for libraries.
# Checks for header files.
AC_CHECK_HEADERS([stdlib.h sys/ioctl.h unistd.h])
# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_SIZE_T
# Checks for library functions.
AC_CHECK_FUNCS([floor pow sqrt])
AC_CONFIG_FILES([Makefile])
AC_OUTPUT

AC_PREREQ(2.52)

AC_INIT([apertium-sl-mk], [0.1.0], [sortiz@users.sourceforge.net])
AM_INIT_AUTOMAKE([apertium-sl-mk], [0.1.0], no-define)
AC_PROG_LN_S
AC_PROG_AWK

m4_define([required_apertium_version], [3.2.0])
PKG_CHECK_MODULES(APERTIUM,   apertium >= required_apertium_version, [], [PKG_CHECK_MODULES(APERTIUM,   apertium-3.2 >= required_apertium_version)])

AP_MKINCLUDE

AC_OUTPUT([Makefile])

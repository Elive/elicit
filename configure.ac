AC_PREREQ(2.59)
AC_INIT([elicit], [1.9], [rephorm@rephorm.com])
AM_INIT_AUTOMAKE([1.6 foreign])

AC_PROG_CC
AM_ENABLE_SHARED
AM_PROG_LIBTOOL
AM_CONFIG_HEADER(sysconfig.h)
AM_BINRELOC

AC_HEADER_STDC
AC_CHECK_HEADERS(math.h)
AC_C_BIGENDIAN


PKG_CHECK_MODULES(ELICIT, [
  evas
  ecore
  ecore-x
  ecore-evas
  ecore-file
  eina
  edje
])

AC_OUTPUT([
Makefile
src/Makefile
src/bin/Makefile
data/Makefile
data/images/Makefile
data/themes/Makefile
data/themes/default/Makefile
data/themes/summer/Makefile
data/themes/spring/Makefile
])

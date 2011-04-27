AC_INIT(node-time, version-0.1.4)
AC_CHECK_MEMBER(struct tm.tm_gmtoff,[AC_DEFINE([HAVE_STRUCT_TM_GMTOFF],[1],[gmtoff in struct tm])],,[#include <time.h>])
AC_CHECK_DECLS([timezone, altzone],[AC_DEFINE([HAVE_TIMEZONE_ALTZONE],[1],[timezone and altzone])],,[#include <time.h>])
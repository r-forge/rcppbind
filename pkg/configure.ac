AC_PREREQ(2.50) dnl require version 2.5+ of autoconf

AC_INIT([rcppbind], 1.0) dnl package name, version

AC_LANG(C++)
AC_REQUIRE_CPP

dnl copy header files to include
dnl copy demo_xxx.cpp, Makefile to src
dnl copy doc.pdf to inst
mkdir -p inst/include
mkdir -p inst/src
mkdir -p inst/doc
cp include/* inst/include
cp src/demo*.cpp src/Makefile.* inst/src
cp doc/rcppbind.pdf inst/doc
cp LICENSE.txt inst

AC_OUTPUT

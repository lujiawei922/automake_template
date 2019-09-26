mylibdir=$(libdir)
#只编译不安装前缀用noinst
mylib_PROGRAMS=libmodulea.so
#依赖的头文件路径
libmodulea_so_CFLAGS= \
	-I../include
#依赖打源文件
libmodulea_so_SOURCES= \
	coreA.c \
	shellA.c
#gcc动态编译
libmodulea_so_LDFLAGS = -shared -fPIC

myincludedir=$(includedir)
include_HEADERS = \
	../include/coreA.h \
	../include/shellA.h

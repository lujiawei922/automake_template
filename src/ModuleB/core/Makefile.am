mylibdir=$(libdir)
#只编译不安装前缀用noinst
mylib_PROGRAMS=libmoduleb.so
#所依赖的头文件路径和标志
libmoduleb_so_CFLAGS= \
	-I../include \
	-I../../ModuleA/include
#所依赖的源文件
libmoduleb_so_SOURCES= \
	coreB.c 
#所依赖的库文件
#libmoduleb_so_LIBADD= \
	../../ModuleA/core/libmodulea.so

#gcc动态编译
libmoduleb_so_LDFLAGS = \
	-shared -fPIC \
	-L../../ModuleA/core/ -lmodulea
	
myincludedir=$(includedir)
include_HEADERS = \
	../include/coreB.h 

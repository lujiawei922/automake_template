#只编译不安装前缀用noinst
noinst_LIBRARIES=libmoduleb.a
#所依赖的头文件路径和标志
libmoduleb_a_CFLAGS= \
	-I../include \
	-I../../ModuleA/include
#所依赖的源文件
libmoduleb_a_SOURCES= \
	coreB.c 
#所依赖的库文件
libmoduleb_a_LIBADD= \
	../../ModuleA/core/libmodulea.a

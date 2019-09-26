#照例添加对应子目录
SUBDIRS = 
SUBDIRS += ModuleA/core ModuleB/core 
#生成打可执行文件
bin_PROGRAMS=app
#依赖的头文件路径
app_CFLAGS= \
	-I./ModuleA/include \
	-I./ModuleB/include
#依赖的源文件
app_SOURCES= \
	main.c
#所需要依赖的库
#app_LDADD= \
	./ModuleA/core/libmodulea.so \
	./ModuleB/core/libmoduleb.so

app_LDFLAGS = \
	-L./ModuleA/core/ -lmodulea \
	-L./ModuleB/core/ -lmoduleb 

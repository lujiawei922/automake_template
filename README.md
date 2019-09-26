# automake生成动态库模板
在基于静态库的基础上进行了动态库的修改，使得这个模板能够支持动态库；\
并且能够通过make install 将生成的可执行文件，动态库，以及头文件一键安装到指定的目录下

# 使用方法
#配置指定路径 \
./configure --prefix="指定安装路径"
#编译安装 \
make;make install

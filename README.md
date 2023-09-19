windows和linux平台下的通用makefile，可以很方便的进行拓展
# 目前支持的功能
windows
```
|
|______编译项目

linux
|
|______编译项目
|
|______生成动态链接库
```
# 编译项目
```
make clean && make -j12
```
# 编译链接库(当前项目是一个链接库项目)
```
make clean && make dylib -j12
```
# 输出目录结构
```
|
|_____build
	|
	|_____bin # 可执行文件
	|
	|_____lib # 动态链接库
	|
	|_____obj # 编译链接文件
```

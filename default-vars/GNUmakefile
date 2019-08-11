# 参考 https://ftp.gnu.org/old-gnu/Manuals/make-3.79.1/html_chapter/make_toc.html
all: 

print-default-var:
	# make 隐含变量 参考 https://www.gnu.org/software/make/manual/html_node/Implicit-Variables.html
	# 默认 C 编译器 
	echo $(CC)
	# 默认汇编器
	echo $(AS)
	# 默认 C++ 编译器
	echo $(CXX)
	# 默认 C 预处理器
	echo $(CPP)
	#echo PROJECT_ROOT = $(dir $(abspath $(lastword $(MAKEFILE_LIST))))

path:
	# 所有的 makefile 文件
	echo $(MAKEFILE_LIST)



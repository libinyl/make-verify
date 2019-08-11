objects = test1.o test2.o

all: $(objects)
	
static-pattern-rule: $(objects)

$(objects): %.o: %.c
	# 静态模式,从最终目标反推所需要的.o 文件和 .c 文件
	$(CC) -c $< -o $@

clean:
	rm -rf $(objects) *.o
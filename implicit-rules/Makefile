objects = test1.o test2.o

target: $(objects)
	$(CC) -o target $(objects)

implicit-rule: $(objects)
	# 隐含规则,把对应的 .c 文件编译为对应的目标文件
test1.o: test1.c
test2.o: test2.c

clean:
	rm -rf $(objects) *.o target
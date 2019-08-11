test1.o: test1.c
	$(CC) -o test1.o $<

clean1.abc:
	# clean1 没有声明为 .PHONY, 所以如果存在 clean1 文件,此命令不会执行.
	rm *.o

.PHONY: clean2.abc
clean2.abc:
	# clean2 被声明为 .PHONY, 所以不管是否存在 clean2 文件, 此命令一定会执行.
	rm *.o
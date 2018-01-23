在使用光盘里提供的Makefile文件对应的 make run 命令快捷实现.nas文件编译成.bin
然后转换成.img最后装载到模拟器运行。在这一过程中Makefile文件里的copy 命令和 del命令
皆报“系统找不到指定文件”错误，对应改成cp 与 rm 命令解决。
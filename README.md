# Linux命令

`cat /proc/pid/maps`或`pmap pid`：查看进程用户态**虚拟内存空间**的实际分布。

`cat /proc/iomem`:查看进程内核态虚拟内存空间的的实际分布。

`sar` 命令当前网络的吞吐率和 PPS

netstat` 或者 `ss 查看socket信息

stat              显示指定文件的详细信息，比ls更详细

uname           显示系统信息

shutdown 	关机

grep	管道

dpkg  	安装

vim三种模式：命令模式、插入模式、编辑模式

chmod

tail	最常用的一种查看方式

绝对路径： 如/etc/init.d

`top`: 实时监控系统中进程的资源占用情况

`ps aux`：查看所有进程的详细状态

`iostat`：查看磁盘占用情况

`strace -p PID`:跟踪进程的系统调用

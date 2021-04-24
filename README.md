# termux

安装vim


pkg update
pkg install vim curl wget git tree -y


pkg  install  vim

修改问候语

vim   $PREFIX/etc/motd


打开进入编辑文件


点键盘上的字母i进入输入模式


修改问候语内容

i  输入模式

回车键或esc退出输入模式

命令行模式输入:冒号:wq

保存修改退出

esc

:wq保存回车退出vim

最后

$ exit

退出重启termux 

即可完成修改问候语
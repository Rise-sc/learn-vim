This is vim2.md
# vim的四个模式
## normal
默认进去
## insert
i,a,o等方法进入insert
## command 
执行vim命令
:输入命令 wq set nu等\
分屏命令 :vs(左右) , :sp(上下)\ 
全局替换 :% s/foo/bar/g 全局替换\
例如:java 在command输入 % s/java/python/g 就可以把文件中的java全部替换为python
## visual 
一般选择块状文本\
normal模式下使用v进入visual 
vim -r .vim2.md.swp用V进入选择行 
使用ctrl+q进行方块选择(不同的终端可能不一样,ctrl+v / ctrl+q )



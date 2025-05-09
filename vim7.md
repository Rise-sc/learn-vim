# vim多文件操作
## Buffer,Windows,Tab
1. buffer打开文件的内存缓冲区 (打开多文件)
2. windows是buffer可视化的分割区域(分割区域)
3. tab可以组织窗口为工作区(归类)

## buffer: 缓存区域
我们写的地方只要不执行w命令则为缓冲区 
:ls  查看当前缓冲区 
默认打开vim1.md文件 
: e vim2.md 打开vim2.md文件   
: e vim3.md 打开vim3.md文件  
: b vim2.md 切换vim2.md文件 
: b vim3.md 切换vim3.md文件  
## windows: 分割区域 
vs : 左右分割  
sp : 上下分割   
:vs vim2.md 左右分割并打开vim2.md  
ctrl+w w 循环切换分割区域  
ctrl+w h,j,k,l 按方向切换区域    
ctrl+w H,L 左右切换区域位置 
## tab:标签页:像网页标签
tabnew vim2.md :在新标签页打开vim2.md 
gt 切换标签页 

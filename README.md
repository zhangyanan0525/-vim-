# -vim-
简单整理一下用过的vim命令啦～


### vim模式


正常模式（按Esc或Ctrl+[进入） 左下角显示文件名或为空

插入模式（按i键进入） 左下角显示--INSERT--

可视模式（按v键进入） 左下角显示--VISUAL--

### vim命令

```
syntax on       开启代码高亮
syntax off      关闭代码高亮
```


```
set hlsearch    开启搜索高亮
set nohlsearch  关闭搜索高亮
```


```
set incsearch   输入搜索字符串的同时进行搜索，一边打字一边搜索
```


```
set ignorecase  搜索时忽略大小写
```


```
set number      显示行号
set nonu        不显示行号
```


```
h j k l 方向
```


```
d  删除 正常模式下按v（逐字）或V（逐行）进入可视模式，然后用jklh命令移动即可选择某些行或字符，再按d即可删除
dd 删除光标所在行
x  删除当前字符
```


```
yy 复制光标所在行
y  正常模式下按v（逐字）或V（逐行）进入可视模式，然后用jklh命令移动即可选择某些行或字符，再按y即可复制
```


```
p 粘贴
```


```
u      （Undo）  撤销上一个操作
Ctrl+r （Redo）  把撤销的那个操作，再做回来
.               重复上一操作
```

```
G gg   文件顶部底部
```


```
:q! 强制退出缓冲区而不保存
:wq! 强制保存文件并退出缓冲区
:x 如果文件有更改，则保存后退出。否则直接退出。
```



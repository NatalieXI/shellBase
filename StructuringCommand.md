# 使用结构化命令
## if-then语句
```
if coommand
then
  commands
fi
```
如果command退出状态码是0（表明执行成功），条件符合。否则不符合
## if-then-else
```
if coommand
then
  commands
else
  commands
fi
```
## 嵌套if
```
if coommand
then
  commands
elif command
then
  commands
fi
```
## test命令
1. test condition
```
if test condition
then
  commands
fi

if [ condition ]
then
  conmands
fi
```
###
test可以判断三类条件
1. 数值比较
2. 字符串比较
3. 文件比较
4. 文件比较最常用（-d file,-e file,-f file,-r file-w file,-x file,file1 -nt file2,file1 -ot file2）

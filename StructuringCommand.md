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

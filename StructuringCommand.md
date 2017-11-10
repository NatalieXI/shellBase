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
### 复合条件测试
1. [condition1] && [condition2]
2. [condition1] || [condition2]
## if-then的高级特性

1. 用于数学表达式的双圆括号((expression))

        1.1. 常见的高级表达式(val++,val--,++val,--val,!,~,**,<<,>>,&,|,&&,||)
    
2. 用于高级字符串处理功能的双方括号[[ expression ]]

        2.1. 双方括号提供了针对字符串比较的高级特性
    
        2.2. 例如[[ $user == r* ]] 匹配了环境变量中以r开头的值


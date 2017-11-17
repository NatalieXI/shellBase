# 正则表达式（sed和gawk）
## BRE模式
### 纯文本
1. echo "this is a test" | sed -n '/s a/p'
2. echo "this is a test" | gawk '/test/{print $1}'

```
[nataliexi@NatalieXI ~]$ echo "this is a test" | gawk '/test/{print $1}'
this
[nataliexi@NatalieXI ~]$ echo "this is a test" | gawk '/test/{print $0}'
this is a test
```
### 特殊字符
### 锚字符
### 点字符
### 字符组
### 排除字符组
### 使用区间
### 特殊字符组
### 星号
## 扩展正则表达式
### 问号
### 加号
### 使用花括号
### 管道符号
### 聚合表达式

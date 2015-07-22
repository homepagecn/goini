# goini
使用Golang解析ini文件

特点
---
1. 支持嵌套
2. 支持注释

ini格式约定
---
[section1]
key1 = value1
key2 = value2

[section2 : section1]
key1 = value3

输出结果为
```
map[section1:map[key1:value1 key2:value2] section2:map[key1:value3 key2:value2]]
```

例子
---


## 管道命令

管道命令就是前一个的输出作为后一段的输入

![](C:\Users\Administrator\AppData\Roaming\marktext\images\2023-11-26-10-57-32-image.png)

awk处理分隔符

![](C:\Users\Administrator\AppData\Roaming\marktext\images\2023-11-26-11-01-36-image.png)

xargs将前方查询出来的值作为 参数输入后续命令 中 -i 表示输入参数 {} 表示占位符

awk -F ' ' '{print $1}'  

<u>将字符串通过' '空格切割 并输出第一个元素</u>

![](C:\Users\Administrator\AppData\Roaming\marktext\images\2023-11-26-11-07-34-image.png)

![](C:\Users\Administrator\AppData\Roaming\marktext\images\2023-11-26-11-09-15-image.png)

2. 数据统计 

用于处理一些程序复杂的逻辑 通过脚本

![](C:\Users\Administrator\AppData\Roaming\marktext\images\2023-11-26-11-16-29-image.png)

![](C:\Users\Administrator\AppData\Roaming\marktext\images\2023-11-26-11-16-34-image.png)

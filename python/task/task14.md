# Python 作业 14



```java

有的时候，工作中，我们需要存档文件， 会拷贝一个目录里面所有的文件到另外的机器上
如果是特别机密的存档文件，比如合约，财务信息等，我们不希望这些目录中的文件有任何修改。

假如有员工偷偷修改了存档的文件，就会和源文件不一致

我们需要实现一个工具，能够快速检测存档目录中的文件和源文件是否有不同。

方法是，为源目录中的所有文件产生一个校验文件，里面记录了所有文件的校验和（使用MD5算法）

这样存档后，如果有人修改任何一个文件， 
运行工具 检查 就能发现 现有文件的校验和 与源文件中的校验文件里面记录的值 不同

网上有类似的工具：  filecheckmd5.exe 
下载地址：https://github.com/jcyrss/songqin-testdev/raw/master/others/softwares/filecheckmd5.zip

要求大家用Python语言开发类似的工具。


实现难点 如下，大家自己到网上搜索解决方法，锻炼自己查询资料，解决问题的能力，

难点1： 图形界面
大家可以使用Python 内置的图形界面库 tkinter 去实现

难点2： md5校验和的概念  和 生成文件md5校验和的方法 （特别是对大文件的支持）

```




## 参考答案，往下翻
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

```python

```

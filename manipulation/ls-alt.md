学习
---
# **ls -alt**

```
$ ls -alt
drwxr-xr-x  3 cc  staff   96 Jan 27 11:23 satire
drwxr-xr-x  4 cc  staff  128 Jan 27 11:23 slapstick
drwxr-xr-x  4 cc  staff  128 Jan 27 11:22 .
drwxr-xr-x  6 cc  staff  192 Jan 27 11:20 ..
```
``-t``选项是根据最后的更新时间来排血文档和目录。

除了分别用每一个选项，像 ``ls -a``或者 ``ls -l``。多个选项可以一起用，像  ``ls -alt``。

这里的 ``ls -alt``用long format， 根据最后的更新时间，列出了所有内容，包括隐藏的文档和目录，

用法
---

  1， 让我们继续学习从命令行去拷贝，移动，移除文档和目录。
  
   指向到目录  drama/biopic/
   ```
   $ cd ../drama/biopic
   ```
   列出当前工作目录里的所有文档和目录。

   2，接着输入：
   ```
   $ cp frida.txt lincoln.txt
   ```
   点击[下一节](cp1.md)去学习这个命令
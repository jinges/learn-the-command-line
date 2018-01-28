学习
---

# **ls -a**

```shell
$ ls -a
.   ..   action   comedy    drama   genres.txt
```
  1, 命令行 ``ls`` 罗列出当前工作目录里的所有文档和目录。

  2， ``-a`` 更新了命令行 ``ls``的默认行为，也罗列出当前工作目录里以点（``.``）开始的所有文档和目录。当只单单使用 ``ls``时，以点开始点文档会被隐藏，不会显示出来。

``-a``是一个选项。选项能更新命令行的默认行为。这里我们用 ``ls -a``去显示当前工作目录里更详细点内容。

除了 ``-a``， ``ls``命令行还有很多选项，这里有三个常用点选项：
  * ``-a`` 列出所有内容，包括隐藏点文件和目录
  * ``-l`` 用 long format 列出一个目录里的所有内容
  * ``-t`` 按照更新时间排序列出文档和目录

让我们练习使用这些选项。

用法
---

  1， 在终端，输入：
  ```
  $ ls -l
  ```

  点击[下一节](ls-l.md)去了解每一列点意思。
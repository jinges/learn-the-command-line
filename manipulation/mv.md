学习
---
# mv

用``mv``命令移动文件。 和  ``cp``的使用方法类似。

```
$ mv superman.txt spuerhero/
```
用``mv``移动单个文件到一个目录， 资源文件作为第一个参数，用目标文件夹作为第二个参数。这里我们移动 **superman.txt** 到 **superhero/** 目录里。

```
$ mv wonderwoman.txt batman.txt superhero/
```
用``mv``移动多个文件到一个目录， 多个资源文件列表作为第一个参数，目标文件夹作为最后的一个参数。 这里我们移动 **wonderwoman.txt** 和 **batman.txt** 到 **superhero/** 目录里。

```
$ mv batman.txt spiderman.txt
```
用 ``mv``重命名文件，旧的文件作为第一个参数，新的文件名作为第二个参数。移动 **batman.txt** 到 **spiderman.txt**, 我们可以更改文件到名字为 **spiderman.txt** 。

用法
---

1, 更改当前目录到 **comedy/slapstick/** 。
列出当前工作目录到所有文件和目录。
 ```
 $ cd ../../comedy/slapstick
 ```

 2, 输入：
 ```
 $ rm waterboy.txt
 ```

 3, 列出当前工作目录到所有文件和目录。你会发现 **waterboy.txt** 被移除了。

 4, 从 **comedy/slapstick/** 指向到父级的 **comedy/** 目录里。

 5, 输入：
 ```
$ rm -r slapstick
 ```

 6, 列出当前工作目录到所有文件和目录。你会发现 **slapstick/** 目录被移除了。

 点击[下一节](rm.md)去学习这些命令是怎么工作的。
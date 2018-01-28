学习
---

# wildcards

```
$ cp * satire/
```

除了用文件名作为参数，我们也可以用像 `` * `` 特殊字符去选择一组文件。 这些特殊的字符被称作通配符。 ``*`` 选择了当前工作目录里的所有文件，所以我们拷贝所有的文件到 **satire/** 目录里。

```
$ cp m*.txt scifi/
```

这里的 ``m*.txt`` 选中了当前工作目录里所有以 “m” 开头和 以 “.txt”结束的文件， 然后拷贝到 **scifi/** 目录里。

用法
---

  1, 除了拷贝文件，我们还可以从命令行里移动文件。

  从当前目录切换到  **action/** 目录里。

  ```
  $ cd ../
  ```

  2, 输入
  ```
  $ mv superman.txt superhero/
  ```
  3, 导航到 **superhero/** 目录里。
  列出当前目录里的所有文档和目录，你会看到 **superman.txt** 在里面。

  4, 这里还有 ``mv``的另一种使用方法。

  从 **action/superhero/** 导航到 **action/** 目录里。

  5， 接着输入：
  ```
  $ mv wonderwoman.txt batman.txt superhero/
  ```

  6, 再指向 **superhero/** 目录里。

  列出当前目录里的所有文档和目录，你会看到 **wonderwoman.txt** 和 **batman.txt** 在里面。

  7, 这里还有一种 ``mv`` 的用法。
  输入：
  ```
  $ mv batman.txt spiderman.txt
  ```

  8, 列出当前目录里的所有文档和目录，你会看到 **batman.txt** 的名字改成了 **spiderman.txt**。
  

  点击[下一节](mv.md) 学习这些命令是怎么工作的。
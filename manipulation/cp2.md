学习
---
# cp 2

```
$ cp biopic/cleopatra.txt historical/
```
拷贝一个文件到一个目录。 用 ``cp`` 带上资源作为第一个参数，目标目录作为第二个参数。这里我们拷贝文档 biopic/cleopatra.txt 到 historical/ 目录。

```
$ cp biopic/ray.txt biopic/notorious.txt historical/
```
拷贝多个文件到一个目录。 我用用 ``cp`` 带上一列资源文件作为第一个参数，最后一个参数是目标目录。 这里我们拷贝文件 biopic/ray.txt 和 biopic/notorious.txt 到  historical/ 目录。

用法
---
   1， 让我们再看下 ``cp`` 的另一种方法。

   指向到 comedy/ 目录

   ```
   $ cd ../../comedy
   ```   
   2，在这个目录里，创建一个叫 shrek.txt的新文档。

   3，接着输入：
   ```
   $ cp * satire/
   ```
   4, 指向目录 satire/ 。
   列出当前工作目录的所有文档和目录。
   在这个目录你可以看到拷贝的 the-office.txt 和 shrek.txt 。我们会在下一节讲解这是怎么实现的。

   5，这里还有一种 ``cp``的使用方法。
   指向到目录 action/， 然后输入：
   ```
  $ cd ../../action/
   ```
   这里指向到上两级目录，然后进入action/目录。

   6， 输入：
   ```
   $ cp m*.txt scifi/
   ```

   7, 更改目录进入到  scifi/ 。
   
   列出当前工作目录里的所有文档和目录。
  
   你会看到拷贝的所有以 ‘m’开头的文档： matrix.txt, matrix-reloaded.txt, 和 matrix-revolutions.txt.

   点击[下一节](wildcards.md) 学习这个工作原理。
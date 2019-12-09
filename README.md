# AllNotebook

cs菜鸡的十万个为什么  

## Git
* [git是什么？github又是什么?他们都有什么用啊？](http://blog.a0z.me/2014/05/21/GitBeginning/)  
版本控制  
当我们在一个目录中运行命令：  
```
$ git init 
# Git初始化的命令，用于新建版本库
```
这个目录中就会默认产生一个新目录：
```
.git/
```
它将默认记录当前目录（直接包含.git的这个目录，下文中叫做“项目目录”）中任何文件的改动。如果把这个版本库删除了，这里面记录的文件版本就都没有了，项目目录中的文件当前是什么样子，那就一直是什么样子，没法恢复到以前的版本了。
如果想让Git忽视项目目录中的什么文件（比如程序缓存等），可以在`.gitignore`中写清楚那些文件。

## CTF
* 余弦の安全技能树简版 (https://evilcos.me/security_skill_tree_basic/index.html)
![](https://evilcos.me/security_skill_tree_basic/security_skill_tree_basic_files/images/%E5%AE%89%E5%85%A8%E6%8A%80%E8%83%BD%E6%A0%91%E7%AE%80%E7%89%88%202.jpg)

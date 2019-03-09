
# spiderexam
 爬虫工程师面试常见问题。
题目共享地址： https://shimo.im/docs/iyZrc3fLimghmrNB/read

 ![image](https://github.com/asyncspider/spiderexam/blob/master/images/example.png) 
 

# 题目与答案征集 
目前问题与答案正在收集中，请大家踊跃参与。
 
目前答案不开放，待问题收集到一定规模，则开放答案，大家可以先尝试做题。
 
 在 issues 处提交你的问题与答案即可，提交格式为：

```
Question:Title - [提供者信息]

Answer:

```

例如：

Question:is 和 == 的区别 - [AsyncIns]

Answer：is 表示的是对象标示符（object identity），而 == 表示的是相等（equality）。
is 的作用是用来检查对象的标示符是否一致，也就是比较两个对象在内存中的地址是否一样，而 == 是用来检查两个对象是否相等。但是为了提高系统性能，对于较小的字符串 Python 会保留其值的一个副本，当创建新的字符串的时候直接指向该副本即可。如：
```
a = 8
b = 8
a is b
```

Question:打印输出当前文件所在目录路径 - [德玛西亚之翼-奎因]

Answer：
```
import os
print(os.path.dirname(os.path.abspath(__file__)))
```





我会每天定时收录到文档中。
 
 我们应当做到题目与答案对应且尽可能的详尽，如：
 ![image](https://github.com/asyncspider/spiderexam/blob/master/images/example.png) 
 
 最后，我们都希望得到一份完整的爬虫工程师面试考点:
 
 ![image](https://github.com/asyncspider/spiderexam/blob/master/images/spiderexam.png) 
 
 这需要我们大家一起努力。如果你想加入到 Github 白名单，请联系 asyncins@aliyun.com
 
 

在使用索引情况下，like ‘关键字%’ 比instr快很多（注意：like ‘%关键字%’就算字段上建了索引也不会用）；

没有索引情况下，like ‘关键字%’ 比instr稍快

没有索引情况下，like ‘%关键字%’比instr稍慢

https://blog.csdn.net/ljj2312/article/details/78217752
https://www.cnblogs.com/chaobest/p/6737901.html
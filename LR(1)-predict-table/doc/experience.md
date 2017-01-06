
- 比较两个数组是否相同
你实现的重点就是要比较两个列表的是否相同。
建议你可以先排序在比较
a.sort()
b.sort()
a==b就会返回True。

如：
>>> a = [(1,1),(2,2),(3,3),(4,4)]
>>> b = [(4,4),(1,1),(2,2),(3,3)]
>>> a==b
False
>>> a.sort()
>>> b.sort()
>>> a
[(1, 1), (2, 2), (3, 3), (4, 4)]
>>> b
[(1, 1), (2, 2), (3, 3), (4, 4)]
>>> a==b
True
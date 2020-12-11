# List 集合
tags: #集合 

> List 集合包括 List 接口和 List 接口的所有实现类。
> List集合中的元素允许重复，各元素的顺序就是对象插入的顺序。
> 用户可通过索引来访问集合中的元素。

## List接口
1. 继承[[Collection]]接口
2. 新增get、set方法

## List接口的实现类

- [ArrayList](ArrayList.md)
    - 实现可变数组
    - 允许保存所有元素，包括null
    - 缺点：插入、删除速度慢
- [[LinkedList]]
    - 链表结构保存对象
    - 缺点：遍历效率低，每次都需从第一个开始
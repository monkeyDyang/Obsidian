# ArrayList
#Java #集合

> [List](List.md)接口的实现类
> 一个**数组队列**，相当于 **动态数组**
> ArrayList中的操作是[[线程]]不安全的

-------------------------------------------------------------------------------
## 构造函数

```java
// 默认构造函数
ArrayList()

// capacity是ArrayList的默认容量大小。当由于增加数据导致容量不足时，容量会添加上一次容量大小的一半。
ArrayList(int capacity)

// 创建一个包含collection的ArrayList
ArrayList(Collection<? extends E> collection)
```

## 遍历方式
**ArrayList支持的3种遍历方式**

(01) 第一种，**通过迭代器遍历**。即通过 [[Iterator]] 去遍历。

```java
Integer value = null;
Iterator iter = list.iterator();
while (iter.hasNext()) {
    value = (Integer)iter.next();
}
```

(02) 第二种，**随机访问，通过索引值去遍历。**
由于 ArrayList 实现了 RandomAccess 接口，它支持通过索引值去随机访问元素。

```java
Integer value = null;
int size = list.size();
for (int i=0; i<size; i++) {
    value = (Integer)list.get(i);        
}
```

(03) 第三种，**for 循环遍历**。如下：

```java
Integer value = null;
for (Integer integ:list) {
    value = integ;
}
```



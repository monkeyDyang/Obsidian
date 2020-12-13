# Collection 接口
#Java #集合 #接口

> Collection 接口是层次结构中的根接口，通常不能直接使用
> 定义了添加元素、删除元素、管理数据的方法
> [List](List.md)接口与[[Set]]接口都继承Collection接口
> 通过迭代器 [[Iterator]]实现

## 常用方法
| 方法名                                    | 说明                                                         |
| ----------------------------------------- | ------------------------------------------------------------ |
| boolean add(E e)                          | 向集合添加元素e，若指定集合元素改变了则返回true              |
| boolean addAll(Collection<? extends E> c) | 把集合C中的元素全部添加到集合中，若指定集合元素改变返回true  |
| void clear()                              | 清空所有集合元素                                             |
| boolean contains(Object o)                | 判断指定集合是否包含对象o                                    |
| boolean containsAll(Collection<?> c)      | 判断指定集合是否包含集合c的所有元素                          |
| boolean isEmpty()                         | 判断指定集合的元素size是否为0                                |
| boolean remove(Object o)                  | 删除集合中的元素对象o,若集合有多个o元素，则只会删除第一个元素 |
| boolean removeAll(Collection<?> c）       | 删除指定集合包含集合c的元素                                  |
| boolean retainAll(Collection<?> c)        | 从指定集合中保留包含集合c的元素,其他元素则删除               |
| int size()                                | 集合的元素个数                                               |
| T[] toArray(T[] a)                        | 将集合转换为T类型的数组                                      |



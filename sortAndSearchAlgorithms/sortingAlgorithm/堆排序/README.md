堆排序也是一种很高效的算法,因其把数组当作二叉树来排序而得名。这个算法会根据以下
信息,把数组当作二叉树来管理。

索引0是树的根节点;
除根节点外,任意节点N的父节点是N/2;
节点L的左子节点是2*L;
节点R的右子节点是2*R+1。



#### 资料
[wikipedia](https://zh.wikipedia.org/wiki/%E5%A0%86%E6%8E%92%E5%BA%8F)


```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```


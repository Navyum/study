

树 Tree

定义：

树是n个节点的有限集，n=0时为空树，

非空树：

1.有且仅有一个root根节点

2.n>1时，其余节点可分为m个互不相交的有限集，每个集合也是一个树，称为子树

相关概念：

层次：节点所在行号，根为1

树的深度：最大叶子节点的所属层次

节点的度：该节点的分支个数，二叉树（0～2）

ADT：


![图片](./IMG/树%20tree.md/d7f45d49.png)


数据结构：


![图片](./IMG/树%20tree.md/332fcd06.png)
![图片](./IMG/树%20tree.md/df5c5447.png)


root的parent设为-1


孩子表示法（孩子数量不确定）：类似哈希表


![图片](./IMG/树%20tree.md/61c08914.png)


包括孩子节点，表头，树结构


![图片](./IMG/树%20tree.md/bf5812de.png)
![图片](./IMG/树%20tree.md/1a07482f.png)


孩子兄弟表示法：（二叉树）


![图片](./IMG/树%20tree.md/855bcc74.png)


节点：


![图片](./IMG/树%20tree.md/09ac30c7.png)



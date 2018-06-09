# 尤克斯特拉算法

尤克斯特拉算法包含4个步骤：

1. 找出最便宜的节点，即可在最短时间内前往的节点。
2. 对于该节点的邻居，检查是否有前往他们的更短路径，如果有，就更新其开销。
3. 重复这个过程，直到对图中的每个节点都这样做了。
4. 计算最终路径。

## 小结

- 广度优先搜索用于在非加权图中查找最短路径。
- 尤克斯特拉算法用于在加权图中查找最短路径。
- 仅当权重为正时尤克斯特拉算法才管用。
- 如果图中包含负权边，请使用贝尔曼-福德算法。
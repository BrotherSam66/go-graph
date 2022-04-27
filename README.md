# go-graph
Graph implementation for go
```
有向/无向
有权重/无权重
有向双向权重可以不同

稠密图==》邻接矩阵
稀疏图==》邻接表

DFS Depth First Search  深度优先遍历
BFS Breadth First Search 广度优先遍历
graphNode

https://blog.csdn.net/weixin_34392843/article/details/88805569

v vertex 顶点
有向|无向图
arc 弧
tail 起点，弧尾
head 终点，弧头

无向图 叫edge 边
度：顶点关联的边的数量
有向图：出度|入度
赋权图 or 网
权 weight

Node : { ID (string), resolved (bool), edges ([]Edge) }  
Edge : { ID (string), start (Node), end (Node), weight (Float64)}  

```


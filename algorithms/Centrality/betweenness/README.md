
# Betweenness

#### [Betweenness Changelog](https://github.com/karimsaraipour/gsql-graph-algorithms/blob/master/algorithms/Centrality/betweenness/CHANGELOG.md) | [Discord](https://discord.gg/vFbmPyvJJN) | [Community](https://community.tigergraph.com) | [TigerGraph Starter Kits](https://github.com/zrougamed/TigerGraph-Starter-Kits-Parser)

## [TigerGraph Betweenness Documentation](https://docs.tigergraph.com/tigergraph-platform-overview/graph-algorithm-library#betweenness-centrality)

## Available Betweenness Algorithms 

* [`tg_betweenness_cent`](https://github.com/karimsaraipour/gsql-graph-algorithms/blob/master/algorithms/Centrality/betweenness/tg_betweenness_cent.gsql)

## Installation 

### Replace `<Betweenness Algorithm>` with desired algorithm listed above 

#### Via TigerGraph CLI

```bash
$ tg box algos install <Betweenness Algorithm>
```

#### Via GSQL terminal

```bash
GSQL > BEGIN
# Paste <Betweenness Algorithm> code after BEGIN command
GSQL > END 
GSQL > INSTALL QUERY <Betweenness Algorithm>
```
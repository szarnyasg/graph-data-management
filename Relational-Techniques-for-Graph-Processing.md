# Graph Processing Using Relational Operators

## Worst-Case Optimal Join (WCOJ) Algorithms and Factorized Query Processing

* `[WCOJ]`: worst-case optimal joins
* `[FACT]`: factorized query processing

## Lectures and Tutorials

* [GraphflowDB and Modern Query Processing Techniques for GDBMSs](https://www.youtube.com/watch?v=Hn2XRv8dU5k), 1-hour lecture by Semih Salihoglu at Pinterest Labs (2021) `[WCOJ]` `[FACT]`
* [From joins to aggregates and optimization problems](https://www.youtube.com/watch?v=KYgG72oQhOw) ([slides](http://www.cs.ox.ac.uk/dan.olteanu/tutorials/Turing-jan18.pdf)), lecture by Dan Olteanu (2018) `[WCOJ]` `[FACT]`
* [From joins to aggregates and optimization problems](https://www.youtube.com/watch?v=uaHSAolWTiI&list=PLVjVSqmQgPG_6XsFfv9sTMd5EpWjkfRiX), lectures series by Dan Olteanu (2018) `[WCOJ]` `[FACT]`
* [Factorised databases](https://www.youtube.com/watch?v=_wUOcDkxAzE), [slides](http://www.cs.ox.ac.uk/dan.olteanu/tutorials/fdb-turing17.pdf), short lecture by Dan Olteanu (2017) `[FACT`]
* SIGMOD 2020 tutorial: [Optimal Join Algorithms Meet Top-k](https://northeastern-datalab.github.io/topk-join-tutorial/) `[WCOJ]`
* [LIquid: Soul of a New Graph Database](https://uwaterloo.ca/data-systems-group/events/dsg-seminar-series-liquid-soul-new-graph-database) by Scott Meyer, presented at the University of Waterloo's DSG Seminar Series
  * [YouTube](https://www.youtube.com/watch?v=wKx-YZn9YQk)
* [Relational databases can handle graphs too! Experiences with optimizing the Umbra RDBMS for LDBC SNB BI](https://youtu.be/cRgbdY3I2i4) ([slides](https://datasets.ldbcouncil.org/event/fifteenth-tuc-meeting/attachments/altan-birler-relational-databases-can-handle-graphs-too.pdf)) by Altan Birler (Technische Universität München), presented at the 15th LDBC TUC

## Papers

* ⚡️ [Graph Processing in RDBMSs](http://sites.computer.org/debull/A17sept/p6.pdf) by Kangfei Zhao, Jeffrey Xu Yu (IEEE Data Eng. Bull., 2017)

## Papers on worst-case optimal joins

### Theory

* [Worst-Case Optimal Join Algorithms](https://dl.acm.org/doi/10.1145/2213556.2213565) (PODS 2012)
* [Skew Strikes Back: New Developments in the Theory of Join Algorithms](https://arxiv.org/abs/1310.3314) (SIGMOD Record 2013)
* [Worst-Case Optimal Join Algorithms](https://dl.acm.org/doi/10.1145/3180143) (Journal of the ACM 2018)
* [Worst-Case Optimal Graph Joins in Almost No Space](http://aidanhogan.com/docs/wco-ring.pdf) (SIGMOD 2021)
* [Optimizing One-Time and Continuous Subgraph Queries using Worst-Case Optimal Joins](https://amine.io/assets/papers/wco-optimizers-tods21.pdf) (ACM TODS 2021)

### Implementation

Papers from the University of Waterloo:

* [Distributed Evaluation of Subgraph Queries Using Worst-case Optimal Low-Memory Dataflows](http://www.vldb.org/pvldb/vol11/p691-ammar.pdf) by Khaled Ammar et al. (VLDB 2017)
* [Optimizing subgraph queries by combining binary and worst-case optimal joins](http://www.vldb.org/pvldb/vol12/p1692-mhedhbi.pdf) by Amine Mhedhbi et al. (VLDB 2019)
* [GRainDB: A Relational-core Graph-Relational DBMS](http://cidrdb.org/cidr2022/papers/p57-jin.pdf) ([recording](https://www.youtube.com/watch?v=KtbZ6YEDvo8)) by Guodong Jin et al. (CIDR 2022)
  * [GRainDB: A Hybrid Graph-Relational DBMS](https://datasets.ldbcouncil.org/event/fourteenth-tuc-meeting/attachments/semih-salihoglu-graindb.pdf) ([recording](https://www.youtube.com/watch?v=FFK3y6vPHJs)) by Semih Salihoglu (LDBC TUC 2021)
* [Integrating Column-Oriented Storage and Query Processing Techniques Into Graph Database Management Systems](https://arxiv.org/pdf/2103.02284.pdf) by Pranjal Gupta et al. (VLDB 2021)
* [Making RDBMSs Efficient on Graph Workloads Through Predefined Joins](https://arxiv.org/pdf/2108.10540.pdf) by Guodong Jin and Semih Salihoglu (VLDB 2022)

Other papers:

* [Adopting Worst-Case Optimal Joins in Relational Database Systems](http://www.vldb.org/pvldb/vol13/p1891-freitag.pdf) Michael Freitag et al. (VLDB 2020): WCOJs in the context of the Umbra compiled columnar RDBMS
* [Towards Multi-way Join Aware Optimizer in SAP HANA](http://www.vldb.org/pvldb/vol13/p3019-wi.pdf) by Sungheun Wi et al. (VLDB 2020)
* [A Worst-Case Optimal Join Algorithm for SPARQL](http://aidanhogan.com/docs/SPARQL_worst_case_optimal.pdf) by Aidan Hogan et al. (ISWC 2019)

## Papers on graph analytics

* [The case against specialized graph analytics engines](http://cidrdb.org/cidr2015/Papers/CIDR15_Paper20.pdf) (CIDR 2015), a paper showing how implementing graph algorithms (SSSP, PageRank, connected components) in T-SQL (Microsoft SQL Server) can outperform the implementations of dedicated graph analytics engines
* [In-database connected component analysis](https://arxiv.org/pdf/1802.09478.pdf) (ICDE 2020), a connected components implementation in SQL

## Papers on data structures and indexing

* [A+ Indexes: Tunable and Space-Efficient Adjacency Lists in Graph Database Management Systems](https://arxiv.org/pdf/2004.00130.pdf) (ICDE 2020)

## Loosely related papers/talks

* [The Relational Data Borg is Learning](http://www.vldb.org/pvldb/vol13/p3502-olteanu.pdf), VLDB 2020 keynote
  * [Slides, part 1](https://fdbresearch.github.io/slides/VLDB2020-keynote1-part1.pdf)
  * [Slides, part 2](https://fdbresearch.github.io/slides/VLDB2020-keynote1-part2.pdf)

## Factorized joins

* [Factorized Databases](https://sigmodrecord.org/publications/sigmodRecord/1606/pdfs/03_principles_Olteanu.pdf) (SIGMOD Record 2016)

## Relational databases and property graphs

* [On Directly Mapping Relational Databases to Property Graphs](http://ceur-ws.org/Vol-2369/short06.pdf), AMW 2019
* SAP HANA Graph: [blog post](https://blogs.sap.com/2020/04/27/create-graphs-on-sap-hana-cloud/), [tutorial](https://developers.sap.com/tutorials/hana-graph-overview-setup.html), using the [`CREATE GRAPH WORKSPACE`](https://help.sap.com/viewer/4fe29514fd584807ac9f2a04f6754767/2.0.03/en-US/e6e1c7e2b9064b05b26572808f941ec4.html) language construct

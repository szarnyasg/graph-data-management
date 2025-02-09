# Literature on graph processing

This page lists scientific works on graph processing.

## Dissertations and Master's thesis works

* [Query, Analysis, and Benchmarking Techniques for Evolving Property Graphs of Software Systems](https://szarnyasg.github.io/phd/szarnyasg-phd-dissertation.pdf) by Gábor Szárnyas – PhD dissertation, BME (2019)
  * ⚡️ Chapter 2 contains the background for graph databases
  * ⭐️ Chapter 8 shows a mapping from openCypher queries to an extended relational algebra (it's also available as a concise [preprint](https://arxiv.org/pdf/1806.07344.pdf))
  * ⭐️ Section 10.5 summarizes the state of research (as of 2018) on mapping from graph queries to relational databases (see Table 10.2)
* 💫 [Analysis and Comparison of Common Graph Query Languages](https://web.archive.org/web/20210119211651id_/https://repositum.tuwien.at/bitstream/20.500.12708/16615/2/Analysis%20and%20Comparison%20of%20Common%20Graph%20Query%20Languages.pdf) by Martin Klampfer, TU Vienna (2020)
* 💫 [A G-CORE Graph Query Language Interpreter](https://homepages.cwi.nl/~boncz/msc/2018-GeorgianaCiocirdel.pdf) by Georgiana Ciocirdel, CWI, VU Amsterdam (2018)
* [Enabling Graph Analysis Over Relational Databases](https://drum.lib.umd.edu/handle/1903/26047) by Konstantinos Xirogiannopoulos – PhD dissertation, UMD (2019)

## Papers

### Graphs as relational data

* [LIquid: The soul of a new graph database, Part 2](https://engineering.linkedin.com/blog/2020/liquid--the-soul-of-a-new-graph-database--part-2): this part of LinkedIn Engineering's two-part series on the LIquid graph database discusses the representation of graphs as relational data and the limitations of naïve approaches ([part 1](https://engineering.linkedin.com/blog/2020/liquid-the-soul-of-a-new-graph-database-part-1) presents an object-oriented representation).

### Graphs and SQL

* [DuckPGQ: Bringing SQL/PGQ to DuckDB](https://www.vldb.org/pvldb/vol16/p4034-wolde.pdf) by Daniel ten Wolde, Gábor Szárnyas, Peter Boncz (VLDB 2023 demo)
* ⚡️ [DuckPGQ: Efficient Property Graph Queries in an analytical RDBMS](https://www.cidrdb.org/cidr2023/papers/p66-wolde.pdf) ([📺 slides](https://www.cidrdb.org/cidr2023/slides/p66-wolde-slides.pdf), [recording](https://www.youtube.com/watch?v=pVklntbGiNo)) by Daniel ten Wolde, Tavneet Singh, Gábor Szárnyas, Peter Boncz (CIDR 2023)
* ⚡️ [Graph Processing in RDBMSs](http://sites.computer.org/debull/A17sept/p6.pdf) by Kangfei Zhao, Jeffrey Xu Yu (IEEE Data Eng. Bull., 2017)
  * Longer version: [All-in-One: Graph Processing in RDBMSs Revisited](https://dl.acm.org/doi/10.1145/3035918.3035943) (SIGMOD 2017)
* ⚡️ [An Algebra and Equivalences to Transform Graph Patterns in Neo4j](http://ceur-ws.org/Vol-1558/paper24.pdf) by Jürgen Hölsch, Michael Grossniklaus (GraphQ 2016)
* ⭐️ [GraphGen: Adaptive Graph Processing using Relational Databases](https://event.cwi.nl/grades/2017/09-Xirogiannopoulos.pdf) by [Konstantinos Xirogiannopoulos](http://www.cs.umd.edu/~kostasx/)
* ⭐️ [Extending In-Memory Relational Database Engines with Native Graph Support](https://openproceedings.org/2018/conf/edbt/paper-17.pdf) by Mohamed S. Hassan, Tatiana Kuznetsova, Hyun Chai Jeong, Walid G. Aref, Mohammad Sadoghi (EDBT 2018) about [GRFusion](https://dl.acm.org/doi/10.1145/3183713.3193541) (SIGMOD demo), [code](https://github.com/purduedb/GRFusion)
* 💫 [Graph Pattern Matching – Do We Have to Reinvent the Wheel?](https://event.cwi.nl/grades2014/08-gubichev.pdf) by Andrey Gubichev, Manuel Then (GRADES 2014) [📺 slides](https://event.cwi.nl/grades2014/08-gubichev-slides.pdf)
* [Join Processing for Graph Patterns: An Old Dog with New Tricks](https://arxiv.org/pdf/1503.04169.pdf) by Dung T. Nguyen, Molham Aref et al. (GRADES 2015)
* [G-SQL: Fast Query Processing via Graph Exploration](http://www.vldb.org/pvldb/vol9/p900-ma.pdf) by Hongbin Ma et al. (VLDB 2016)
* [Cytosm: Declarative Property Graph Queries Without Data Migration](https://event.cwi.nl/grades/2017/04-Steer.pdf) by Benjamin A. Steer et al. (GRADES 2017)
* [PGQL: a property graph query language](https://event.cwi.nl/grades/2016/07-VanRest.pdf) by Oskar van Rest et al. (GRADES 2016)
* [Extending SQL for Computing Shortest Paths](https://ir.cwi.nl/pub/27563/27563.pdf) by Dean De Leo and Peter Boncz (GRADES 2017), talk at the LDBC TUC 2017, [📺 slides](https://pub-383410a98aef4cb686f0c7601eddd25f.r2.dev/event/ninth-tuc-meeting/attachments/59277315/75628546.pdf)
* [GraphWrangler: An Interactive Graph View on Relational Data](https://dl.acm.org/doi/abs/10.1145/3299869.3320232), demo paper (SIGMOD 2019)
* [Towards compiling graph queries in relational engines](https://dl.acm.org/doi/pdf/10.1145/3315507.3330200) (DBPL 2019)

### Graphs and SPARQL

* [G-SPARQL: a hybrid engine for querying large attributed graphs](https://dl.acm.org/doi/10.1145/2396761.2396806) by Sherif Sakr, Sameh Elnikety, Yuxiong He (CIKM 2012)

### Semantics of query languages

* openCypher
  * [Cypher: An Evolving Query Language for Property Graphs](http://homepages.inf.ed.ac.uk/libkin/papers/sigmod18.pdf) by Nadime Francis et al. (SIGMOD 2018), [technical report on semantics](https://arxiv.org/pdf/1802.09984.pdf)
  * [Updating Graph Databases with Cypher](http://www.vldb.org/pvldb/vol12/p2242-green.pdf) by Alastair Green et al. (VLDB 2019)
* G-CORE
  * [G-CORE: A Core for Future Graph Query Languages](https://arxiv.org/pdf/1712.01550.pdf) by Renzo Angles et al. (SIGMOD 2018)

### Overview papers and posts

* ⚡️ [Graph query languages](https://szarnyasg.github.io/posts/graph-query-languages/) by Gábor Szárnyas (2021), the top 10 graph query languages
* [Demystifying Graph Databases: Analysis and Taxonomy of Data Organization, System Designs, and Graph Queries](https://arxiv.org/pdf/1910.09017.pdf) by Maciej Besta et al. (preprint, 2020)
* [Foundations of Modern Graph Query Languages](https://arxiv.org/pdf/1610.06264.pdf) by Renzo Angles et al. (ACM CSUR, 2017)
* [The ubiquity of large graphs and surprising challenges of graph processing: Extended survey](https://link.springer.com/article/10.1007/s00778-019-00548-x) by Siddhartha Sahu et al. (VLDBJ 2020)

## Talks

* ⚡️ 📺 [Graph database applications with SQL/PGQ](https://download.oracle.com/otndocs/products/spatial/pdf/AnD2020/AD_Develop_Graph_Apps_SQL_PGQ.pdf) by Jan Michels, Andy Witkowski, Oracle (2020)
* ⚡️ 📺 [Property Graph Extensions for the SQL Standard](https://pub-383410a98aef4cb686f0c7601eddd25f.r2.dev/event/twelfth-tuc-meeting/attachments/106233859/111706119.pdf) by Vasileios Trigonakis and Oskar van Rest, Oracle (LDBC TUC 2019)

## Related

* ⚡️ 📺 [PGQL Introduction and Deep Dive](https://www.oracle.com/a/tech/docs/asktom-pgql-introduction-deep-dive.pdf), an overview of PGQL by Melli Annamalai and Ryota Yamanaka, Oracle (2020)

## Graph query engine implementations

* [Morpheus: Cypher for Apache Spark](https://github.com/opencypher/morpheus) (abandoned) 📺 [slides](https://www.slideshare.net/databricks/neo4j-morpheus-interweaving-documents-tables-and-and-graph-data-in-spark-with-alastair-green-and-mats-rydberg)
* [AgensGraph](https://github.com/bitnine-oss/agensgraph)
* [Apache AGE](https://age.apache.org/)

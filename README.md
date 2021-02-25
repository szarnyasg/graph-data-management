# Pointers for SQL/PGQ

A bunch of pointers to navigate the literature and resources on graph query languages, particularly SQL/PGQ.

Legend:

* :zap: best for getting started
* :star: probably worth a read
* :dizzy: worth skimming through
* :tv: slides

## Dissertations and Master's thesis works

* [Query, Analysis, and Benchmarking Techniques for Evolving Property Graphs of Software Systems](https://szarnyasg.github.io/phd/szarnyasg-phd-dissertation.pdf) by Gábor Szárnyas – PhD dissertation, BME (2019)
  * :zap: Chapter 2 contains the background for graph databases
  * :star: Chapter 8 shows a mapping from openCypher queries to an extended relational algebra (it's also available as a concise [preprint](https://arxiv.org/pdf/1806.07344.pdf))
  * :star: Section 10.5 summarizes the state of research (as of 2018) on mapping from graph queries to relational databases (see Table 10.2) 
* :dizzy: [Analysis and Comparison of Common Graph Query Languages](https://repositum.tuwien.at/bitstream/20.500.12708/16615/2/Analysis%20and%20Comparison%20of%20Common%20Graph%20Query%20Languages.pdf) by Martin Klampfer, TU Vienna (2020)
* :dizzy: [A G-CORE Graph Query Language Interpreter](https://homepages.cwi.nl/~boncz/msc/2018-GeorgianaCiocirdel.pdf) by Georgiana Ciocirdel, CWI, VU Amsterdam (2018)
* [Enabling Graph Analysis Over Relational Databases](https://drum.lib.umd.edu/handle/1903/26047) by Konstantinos Xirogiannopoulos – PhD dissertation, UMD (2019)
* [Advanced Techniques for the Implementation of Model Transformation Systems](https://repozitorium.omikk.bme.hu/handle/10890/754?locale-attribute=en) (model/graph transformations in relational databases) by Gergely Varró – PhD dissertation, BME (2008)

## Papers

### Graphs and SQL

* :zap: [Graph Processing in RDBMSs](http://sites.computer.org/debull/A17sept/p6.pdf) by Kangfei Zhao, Jeffrey Xu Yu (IEEE Data Eng. Bull., 2017)
  * Longer version: [All-in-One: Graph Processing in RDBMSs Revisited](https://dl.acm.org/doi/10.1145/3035918.3035943) (SIGMOD 2017)
* :zap: [An Algebra and Equivalences to Transform Graph Patterns in Neo4j](http://ceur-ws.org/Vol-1558/paper24.pdf) by Jürgen Hölsch, Michael Grossniklaus (GraphQ 2016)
* :star: [GraphGen: Adaptive Graph Processing using Relational Databases](https://event.cwi.nl/grades/2017/09-Xirogiannopoulos.pdf) by [Konstantinos Xirogiannopoulos](http://www.cs.umd.edu/~kostasx/)
* :star: [Extending In-Memory Relational Database Engines with Native Graph Support](https://openproceedings.org/2018/conf/edbt/paper-17.pdf) by Mohamed S. Hassan, Tatiana Kuznetsova, Hyun Chai Jeong, Walid G. Aref, Mohammad Sadoghi (EDBT 2018) about [GRFusion](https://dl.acm.org/doi/10.1145/3183713.3193541) ([code](https://github.com/purduedb/GRFusion))
* :dizzy: [Graph Pattern Matching - Do We Have to Reinvent the Wheel?](https://event.cwi.nl/grades2014/08-gubichev.pdf) by Andrey Gubichev, Manuel Then (GRADES 2014) :tv: [slides](https://event.cwi.nl/grades2014/08-gubichev-slides.pdf)
* [Join Processing for Graph Patterns: An Old Dog with New Tricks](https://arxiv.org/pdf/1503.04169.pdf) by Dung T. Nguyen, Molham Aref et al. (GRADES 2015)
* [G-SQL: Fast Query Processing via Graph Exploration](http://www.vldb.org/pvldb/vol9/p900-ma.pdf) by Hongbin Ma et al. (VLDB 2016)
* [Cytosm: Declarative Property Graph Queries Without Data Migration](https://event.cwi.nl/grades/2017/04-Steer.pdf) by Benjamin A. Steer et al. (GRADES 2017)
* [PGQL: a property graph query language](https://event.cwi.nl/grades/2016/07-VanRest.pdf) by Oskar van Rest et al. (GRADES 2016)
* [Extending SQL for Computing Shortest Paths](https://ir.cwi.nl/pub/27563/27563.pdf) by Dean De Leo and Peter Boncz (GRADES 2017) :tv: [[talk at the LDBC TUC 2017]](http://wiki.ldbcouncil.org/pages/viewpage.action?pageId=59277315&preview=/59277315/75628546/de%20Leo%20presentation%202017-02-09__pdf.pdf)
* [GraphWrangler: An Interactive Graph View on Relational Data](https://cs.uwaterloo.ca/~ssalihog/papers/anzum-graphwrangler.pdf), demo paper (SIGMOD 2019)

### Graphs and SPARQL

* [G-SPARQL: a hybrid engine for querying large attributed graphs](https://dl.acm.org/doi/10.1145/2396761.2396806) by Sherif Sakr, Sameh Elnikety, Yuxiong He (CIKM 2012)

### Semantics of graph query languages

* openCypher
  * [Cypher: An Evolving Query Language for Property Graphs](http://homepages.inf.ed.ac.uk/libkin/papers/sigmod18.pdf) by Nadime Francis et al. (SIGMOD 2018)
    * [Cypher semantics](https://arxiv.org/pdf/1802.09984.pdf)
  * [Updating Graph Databases with Cypher](http://www.vldb.org/pvldb/vol12/p2242-green.pdf) by Alastair Green et al. (VLDB 2019)
* G-CORE
  * [G-CORE: A Core for Future Graph Query Languages](https://arxiv.org/pdf/1712.01550.pdf) by Renzo Angles et al. (SIGMOD 2018)

### Overview papers and talks

* [Demystifying Graph Databases: Analysis and Taxonomy of Data Organization, System Designs, and Graph Queries](https://arxiv.org/pdf/1910.09017.pdf) by Maciej Besta et al. (preprint, 2020)
* [Foundations of Modern Graph Query Languages](https://dblp.org/rec/journals/csur/AnglesABHRV17.html?view=bibtex) by Renzo Angles et al. (ACM CSUR, 2017)
* [A Survey Of Current Property Graph Query Languages](https://homepages.cwi.nl/~boncz/job/gql-survey.pdf) by Peter Boncz (2020)

## Technical reports

* [Translating openCypher Queries to SQL](https://www.db.bme.hu/sql-for-graphs/c2s.pdf) by Márton Elekes et al. (2018)
* [Formalisation of openCypher Queries in Relational Algebra (Extended Version)](https://repozitorium.omikk.bme.hu/handle/10890/5395) by Gábor Szárnyas, József Marton (2017)

## Posts, encyclopedia entries

* [PostgreSQL, Oracle ... graph query language standards adoption begins](https://www.linkedin.com/pulse/postgresql-oracle-graph-query-language-standards-adoption-green/) by Alastair Green (2020)
* [GQL Wikipedia page](https://en.wikipedia.org/wiki/GQL_Graph_Query_Language)
## Talks

* :zap: :tv: [The Linked Data Benchmark Council](https://docs.google.com/presentation/d/1oXKh94R4myUV5RvgeXn7OzhbveAn9Dg1Q4LlOkFrSko/) by Various Artists (2020)
* :zap: :tv: [Graph database applications with SQL/PGQ](https://download.oracle.com/otndocs/products/spatial/pdf/AnD2020/AD_Develop_Graph_Apps_SQL_PGQ.pdf) by Jan Michels, Andy Witkowski (2020)
* :zap: :tv: [Property Graph Extensions for the SQL Standard](http://wiki.ldbcouncil.org/pages/viewpage.action?pageId=106233859&preview=/106233859/111706119/ldbc_tuc_2019_sql-pgq.pdf) by Vasileios Trigonakis and Oskar van Rest (LDBC TUC 2019)
* :tv: [Mapping Graph Queries to PostgreSQL](https://www.slideshare.net/szarnyasg/mapping-graph-queries-to-postgresql) by Gábor Szárnyas et al. (2018)

## Implementations

* [Morpheus: Cypher for Apache Spark](https://github.com/opencypher/morpheus) (abandoned) :tv: [slides](https://www.slideshare.net/databricks/neo4j-morpheus-interweaving-documents-tables-and-and-graph-data-in-spark-with-alastair-green-and-mats-rydberg)
* [CYpher TO Sql Mapper (Cytosm)](https://github.com/cytosm/cytosm) (abandoned)
* [ingraph: incremental graph queries](http://github.com/ftsrg/ingraph) (`cypher-to-sql` branch, abandoned)
* [AgensGraph](https://github.com/bitnine-oss/agensgraph)
* [G-Core Spark](https://github.com/ldbc/gcore-spark) (G-Core on Spark + GraphX)

## Languages

* :zap: [Graph query languages](https://szarnyasg.github.io/posts/graph-query-languages/) by Gábor Szárnyas (2021), the top 10 graph query languages

## Venues

Venues where interesting graph/SQL papers are most likely to appear:
* Major database conferences: SIGMOD, VLDB, ICDE, and EDBT.
* [Workshops](https://www.google.com/maps/d/viewer?mid=19_fi4fV-3-PZkNWCCcmhU86ct2EZXbgo&ll=3.021282693104767%2C0&z=2): GRADES/GRADES-NDA (SIGMOD workshop), GraphQ (EDBT workshop, discountinued), GDM (ICDE workshop, discontinued)
* Industry events: LDBC Technical User Community (TUC) meetings

## Podcast

* [Alastair Green on GQL: the Graph Query Language – The Graph Show](https://www.youtube.com/watch?v=2sLTQQel4NM)
  * [Query languages, Cypher, SQL/PGQ from 25:15 (~8 minutes)](https://youtu.be/2sLTQQel4NM?t=1515)

## Misc papers and talks

* [On Directly Mapping Relational Databases to Property Graphs](http://ceur-ws.org/Vol-2369/short06.pdf), AMW 2019
* SAP HANA Graph: [blog post](https://blogs.sap.com/2020/04/27/create-graphs-on-sap-hana-cloud/), [tutorial](https://developers.sap.com/tutorials/hana-graph-overview-setup.html), using the [`CREATE GRAPH WORKSPACE`](https://help.sap.com/viewer/4fe29514fd584807ac9f2a04f6754767/2.0.03/en-US/e6e1c7e2b9064b05b26572808f941ec4.html) language construct

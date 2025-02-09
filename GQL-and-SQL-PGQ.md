# Pointers for GQL and SQL/PGQ

This page contains pointers to the GQL (Graph Query Language) standard and the SQL/PGQ extension of the SQL standard. Both allow querying property graphs using the visual graph syntax (a.k.a. ASCII art syntax) popularized by [Cypher](https://en.wikipedia.org/wiki/Cypher_(query_language)).

## Implementations

### Systems supporting GQL and SQL/PGQ

| System | Language | Developed in |
|-|-|-|
| [Oracle 23ai](https://oracle-base.com/articles/23/sql-property-graphs-and-sql-pgq-23) | SQL/PGQ | industry |
| [Google Cloud Spanner Graph](https://cloud.google.com/blog/products/databases/announcing-spanner-graph) | GQL | industry |
| [DuckPGQ](https://github.com/cwida/duckpgq-extension) | SQL/PGQ | academia |

See also the joint announcement blog post [Neo4j](https://neo4j.com/blog/cypher-path-gql/) and [AWS Neptune](https://aws.amazon.com/blogs/database/gql-the-iso-standard-for-graphs-has-arrived/).

### GQL resources

See the [opengql GitHub organization](https://github.com/opengql) (maintained by LDBC) for resources to implement GQL.

* [grammar](https://github.com/opengql/grammar): ANTLR Grammar and related content for GQL.
* [editor](https://github.com/opengql/editor): GQL Code Editor.
* [railroad](https://github.com/opengql/railroad): Railroad diagrams for the GQL language

See also the [GQL Parser prototype](https://github.com/OlofMorra/GQL-parser) from 2021 by Olof Morra (TU Eindhoven)
  * [thesis](https://github.com/OlofMorra/GQL-parser/blob/main/src/main/resources/report/A%20Semantics%20of%20GQL;%20a%20New%20Query%20Language%20forProperty%20Graphs%20Formalized.pdf)
  * [presentation](https://github.com/OlofMorra/GQL-parser/blob/main/src/main/resources/Presentation/Final_presentation_GQL.pdf)

## Standardization process

* Property Graph Standards, Process & Timing by Keith Hare
  * [14th LDBC TUC (2021)](https://datasets.ldbcouncil.org/event/fourteenth-tuc-meeting/attachments/keith-hare-database-language-standards-structure-and-process-sql-pgq.pdf) – [🎥 recording](https://www.youtube.com/watch?v=ZgFCuzods4g)
  * [15th LDBC TUC (2022)](https://datasets.ldbcouncil.org/event/fifteenth-tuc-meeting/attachments/keith-hare-property-graph-standards-process-and-timing.pdf) – [🎥 recording](https://www.youtube.com/watch?v=xFVD3LWnKlc)
  * [16th LDBC TUC (2023)](https://datasets.ldbcouncil.org/event/sixteenth-tuc-meeting/attachments/keith-hare-an-update-on-the-gql-and-sql-pgq-standards-efforts.pdf) – [🎥 recording](https://www.youtube.com/watch?v=LQYkal_0j6E)
* [Pattern matching in GQL and SQL/PGQ](https://datasets.ldbcouncil.org/event/fifteenth-tuc-meeting/attachments/leonid-libkin-pattern-matching-in-gql-and-sql-pgq.pdf) by Leonid Libkin (2022) – [🎥 recording](https://www.youtube.com/watch?v=OvGsa0qLANE)
* [The Upcoming GQL Standard](https://zenodo.org/record/4903293) by Stefan Plantikow (2021)
* [Towards GQL 1: Status report on the upcoming ISO/IEC graph query language standard](https://datasets.ldbcouncil.org/event/fourteenth-tuc-meeting/attachments/stefan-plantikow-gql.pdf) by Stefan Plantikow (2021) – [🎥 recording](https://www.youtube.com/watch?v=z0pN5NwKsgc)
* [An overview of GQL](https://datasets.ldbcouncil.org/event/fifteenth-tuc-meeting/attachments/petra-selmer-towards-gql-v1-a-property-graph-query-language-standard.pdf) by Petra Selmer (2022) – [🎥 recording](https://www.youtube.com/watch?v=tncf2FgyIyo)
* [GQL 2.0: A technical manifesto](https://datasets.ldbcouncil.org/event/fifteenth-tuc-meeting/attachments/alastair-green-gql-2.0-a-technical-manifesto.pdf) by Alastair Green (2022) – [🎥 recording](https://www.youtube.com/watch?v=upIvpYy8C2g)

## Online Resources

* [GQL Standard](https://www.gqlstandards.org/)
* [The GQL Manifesto](https://gql.today/)
* [GQL Wikipedia page](https://en.wikipedia.org/wiki/GQL_Graph_Query_Language)

## Semantics

* [Graph Pattern Matching in GQL and SQL/PGQ](https://arxiv.org/pdf/2112.06217.pdf) (preprint, 2021; [paper at SIGMOD 2022](https://dl.acm.org/doi/abs/10.1145/3514221.3526057)) by Alin Deutsch et al. See the related presentation by Leonid Libkin (ENS Paris): [📺 slides](https://datasets.ldbcouncil.org/event/fifteenth-tuc-meeting/attachments/leonid-libkin-pattern-matching-in-gql-and-sql-pgq.pdf), [🎥 recording](https://youtu.be/OvGsa0qLANE)

## Posts, talks, podcasts

* [SQL ... and now GQL](https://www.linkedin.com/pulse/sql-now-gql-alastair-green/) (2019) by Alastair Green
* [GQL and openCypher: the road ahead](https://s3.amazonaws.com/artifacts.opencypher.org/website/ocim5/videos/oCIM5-day1-3+Alastair+Green+-+GQL+and+openCypher+(21min).mp4) (2019) by Alastair Green
* [PostgreSQL, Oracle ... graph query language standards adoption begins](https://www.linkedin.com/pulse/postgresql-oracle-graph-query-language-standards-adoption-green/) (2020) by Alastair Green
* [Alastair Green on GQL: the Graph Query Language – The Graph Show](https://www.youtube.com/watch?v=2sLTQQel4NM)
  * [Query languages, Cypher, SQL/PGQ from 25:15 (~8 minutes)](https://youtu.be/2sLTQQel4NM?t=1515)

# About

This is a set of user-defined functions that DBI + RPostgres users would find useful.
They take similar arguments to DBI functions and behave similarly. The source codes are found in [scr/def.Rmd](https://github.com/Shena4746/r-functions-on-dbi/blob/main/scr/02-def.Rmd).

[This article](https://shena4746.github.io/r-functions-on-dbi/) provides an overview of each function, its definition code, and examples.

Some familiarity with DBI is assumed since they all heavily rely on it. For more information on these packages, please refer to the articles in references.

## Functions included

- Connections
  - Issue a connection
  - Disconnect connections at once
- Views
  - Create a view
  - List view
  - Test existence of a view
  - Drop a view
- Misc
  - Free resources
  - Drop a table with options

## References

Introduction

- [巨大なデータがSQLサーバーにあるときに、Rでどう立ち向かうかマニュアル：dbplyrパッケージを中心として](https://yutatoyama.github.io/note/intro_R_for_SQL.html)
- [Introduction to dbplyr](https://dbplyr.tidyverse.org/articles/dbplyr.html)
- [R: Working with Databases](https://nuitrcs.github.io/databases_workshop/r/r_databases.html)
- [Introduction to DBI](https://dbi.r-dbi.org/articles/dbi)

DBI

- [RSQLite & DBIの使い方](http://delta0726.web.fc2.com/packages/database/00_RSQLite.html)
- [DBI specification](https://dbi.r-dbi.org/articles/spec)
- [DBI: R Database Interface .pdf](https://cran.r-project.org/web/packages/DBI/DBI.pdf)
- [Code Examples for DBI and RPostgres](https://shena4746.github.io/code-examples-dbi-rpostgres/)

RPostgres

- [RPostgres - Reference](https://rpostgres.r-dbi.org/reference/index.html)

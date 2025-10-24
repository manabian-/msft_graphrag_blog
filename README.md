## Overview

Unofficial fork of ianormy/msft_graphrag_blog (original: https://github.com/ianormy/msft_graphrag_blog).

Modified to run on Databricks replace Elasticsearch with Databricks Vector Search.

Original work by Ian Ormesher; this fork is distributed under GPL-3.0 — see [LICENSE](https://github.com/ianormy/msft_graphrag_blog/blob/main/README.md).

## What's Changed

* Modified `by_databricks/01_create_local_global`, based on `Part3/create_local_global`, as follows:
  * Replaced Elasticsearch-based operations with Mosaic AI Vector Search.
  * Replaced operations using the LLM Studio API with Mosaic AI Model Serving.
* Added `by_databricks/00_setup` to set up the environment for running on Databricks with GraphDB (Graphwise Sandbox).
* Added `by_databricks/00_config` to hold shared configuration values.


## Services Used

- [Databricks Free Edition](https://www.databricks.com/learn/free-edition)
- [Graphwise Sandbox(GraphDB)](https://sandbox.graphwise.ai/login?_gl=1*gp2m4o*_gcl_au*MjA1NzM5MDEwNS4xNzYxMTQ4MTAy)


## Detailed Guide

For a step-by-step walkthrough (Japanese):

- [Databricks と GraphDB にて Microsoft GraphRAG with an RDF Knowledge Graph の記事を実行する方法](https://qiita.com/manabian/items/3858945b6aac5d733660)


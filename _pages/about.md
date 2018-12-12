---
layout: single
title: About
permalink: /about/
---

ASTROIDE is a distributed data server
tailored for the management of large volume of astronomical data
and concentrates on query processing and optimization. ASTROIDE
stands for ASTROnomical In-memory Distributed Engine. It is designed as an extension of Apache Spark, and takes into account
the peculiarities of the data and the queries related to astronomical surveys and catalogs.

ASTROIDE includes the following extensions over
Spark:

* Index and partitioning support for astronomical data.
It combines data partitioning with an indexing
technique adapted to astronomical data (HEALPix pixelization), in order to speed-up query processing time.

* Astronomical operators. It proposes efficient and scalable
cone search, kNN search, cross-match, and kNN join algorithms tailored to the proposed physical data organization.

* High-level data access. It supports the data access and query using the most common astronomical query language ADQL.

* Astronomical query optimization. It extends the Catalyst optimizer and exploits partition pruning for astronomical
operators. It introduces new physical and logical optimizations to optimize query execution plans using transformation rules and strategies.


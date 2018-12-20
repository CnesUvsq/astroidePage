---
layout: page
title: About
permalink: /about/
---

ASTROIDE, a distributed data server
tailored for the management of large volume of astronomical data
and concentrate on query processing and optimization. ASTROIDE
stands for ASTROnomical In-memory Distributed Engine. It is de-
signed as an extension of Apache Spark, and takes into account
the peculiarities of the data and the queries related to astronomical
surveys and catalogs.

Our system includes the following extensions over
Spark:
• Index and partitioning support for astronomical data.
Our system combines data partitioning with an indexing
technique adapted to astronomical data (HEALPix pixeliza-
tion), in order to speed-up queries processing time.
• Astronomical operators. We design eicient and scalable
cone search, kNN search, cross-match, and kNN join algo-
rithms tailored to our physical data organization.
• High-level data access. Our framework supports the data
access and query using the most common astronomical query
language ADQL.
• Astronomical query optimization. We extend the Cata-
lyst optimizer and exploit partition tuning for astronomical
operators. We introduce new physical and logical optimiza-
tions to optimize query execution plans using transformation
rules and strategies.


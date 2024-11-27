---
author: akashraokm
ms.author: akashrao
ms.reviewer: maghan, randolphwest
ms.date: 11/26/2024
ms.service: azure-database-postgresql
ms.subservice: flexible-server
ms.topic: include
---

## List of extensions

Below is the list of extensions available.
### address_standardizer

[address_standardizer](http://postgis.net/docs/manual-2.5/Address_Standardizer.html) is used to parse an address into constituent elements. Generally used to support geocoding address normalization step.

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### address_standardizer_data_us

[address_standardizer_data_us](http://postgis.net/docs/manual-2.5/Address_Standardizer.html) is the Address Standardizer US dataset example.                                                               

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### age

[age](https://age.apache.org/) (Preview) provides graph database capabilities                                                                                                                              

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | N/A                |
| 16 | 1.5.0 <sup>1</sup>  |
| 15 | 1.5.0 <sup>1</sup>  |
| 14 | 1.5.0 <sup>1</sup>  |
| 13 | 1.5.0 <sup>1</sup>  |
| 12 | N/A                 |
| 11 | N/A                |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### amcheck

[amcheck](https://www.postgresql.org/docs/13/amcheck.html) provides functions for verifying relation integrity.                                                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.4                |
| 16 | 1.3                 |
| 15 | 1.3                 |
| 14 | 1.3                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.1                |



### anon

[anon](https://postgresql-anonymizer.readthedocs.io) (Preview) provides data anonymization tools.                                                                                                          

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.3.2 <sup>1</sup> |
| 16 | 1.3.2 <sup>1</sup>  |
| 15 | 1.3.2 <sup>1</sup>  |
| 14 | 1.3.2 <sup>1</sup>  |
| 13 | 1.3.2 <sup>1</sup>  |
| 12 | 1.3.2 <sup>1</sup>  |
| 11 | 1.3.2 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### azure_ai

[azure_ai](../../flexible-server/generative-ai-azure-overview.md) provides Azure AI and ML Services integration for PostgreSQL.                                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | N/A                |
| 16 | 1.1.0               |
| 15 | 1.1.0               |
| 14 | 1.1.0               |
| 13 | 1.1.0               |
| 12 | 1.1.0               |
| 11 | N/A                |



### azure_storage

[azure_storage](../../flexible-server/concepts-storage-extension.md) provides Azure integration for PostgreSQL.                                                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | N/A                |
| 16 | 1.5 <sup>1</sup>    |
| 15 | 1.5 <sup>1</sup>    |
| 14 | 1.5 <sup>1</sup>    |
| 13 | 1.5 <sup>1</sup>    |
| 12 | 1.5 <sup>1</sup>    |
| 11 | N/A                |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### bloom

[bloom](https://www.postgresql.org/docs/current/bloom.html) provides an index access method based on Bloom filters.                                                                                        

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### btree_gin

[btree_gin](https://www.postgresql.org/docs/current/btree-gin.html) provides support for indexing common datatypes in GIN.                                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.3                |
| 16 | 1.3                 |
| 15 | 1.3                 |
| 14 | 1.3                 |
| 13 | 1.3                 |
| 12 | 1.3                 |
| 11 | 1.3                |



### btree_gist

[btree_gist](https://www.postgresql.org/docs/current/btree-gist.html) provides support for indexing common datatypes in GiST.                                                                              

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.7                |
| 16 | 1.7                 |
| 15 | 1.7                 |
| 14 | 1.6                 |
| 13 | 1.5                 |
| 12 | 1.5                 |
| 11 | 1.5                |



### citext

[citext](https://www.postgresql.org/docs/current/citext.html) is a data type for case-insensitive character strings.                                                                                       

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.6                |
| 16 | 1.6                 |
| 15 | 1.6                 |
| 14 | 1.6                 |
| 13 | 1.6                 |
| 12 | 1.6                 |
| 11 | 1.5                |



### cube

[cube](https://www.postgresql.org/docs/current/cube.html) is a data type for multidimensional cubes.                                                                                                       

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.5                |
| 16 | 1.5                 |
| 15 | 1.5                 |
| 14 | 1.5                 |
| 13 | 1.4                 |
| 12 | 1.4                 |
| 11 | 1.4                |



### dblink

[dblink](https://www.postgresql.org/docs/current/dblink.html) to connect to other PostgreSQL databases from within a database.                                                                             

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.2                |

> [!NOTE]
> Read the special considerations for extension [dblink](../concepts-extensions-considerations.md#dblink) in Flexible Server.


### dict_int

[dict_int](https://www.postgresql.org/docs/current/dict-int.html) provides a text search dictionary template for integers.                                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### dict_xsyn

[dict_xsyn](https://www.postgresql.org/docs/current/dict-xsyn.html) provides a text search dictionary template for extended synonym processing.                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### earthdistance

[earthdistance](https://www.postgresql.org/docs/current/earthdistance.html) calculates great-circle distances on the surface of the Earth.                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.1                |
| 16 | 1.1                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.1                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### fuzzystrmatch

[fuzzystrmatch](https://www.postgresql.org/docs/current/fuzzystrmatch.html) determines similarities and distance between strings.                                                                          

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.1                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### hstore

[hstore](https://www.postgresql.org/docs/current/hstore.html) is a data type for storing sets of (key, value) pairs.                                                                                       

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.8                |
| 16 | 1.8                 |
| 15 | 1.8                 |
| 14 | 1.8                 |
| 13 | 1.7                 |
| 12 | 1.6                 |
| 11 | 1.5                |



### hypopg

[hypopg](https://github.com/HypoPG/hypopg) provides hypothetical indexes for PostgreSQL.                                                                                                                   

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.4.0              |
| 16 | 1.4.0               |
| 15 | 1.4.0               |
| 14 | 1.4.0               |
| 13 | 1.4.0               |
| 12 | 1.4.0               |
| 11 | 1.4.0              |



### intagg

[intagg](https://www.postgresql.org/docs/current/intagg.html) is an obsolete extension that provides an integer aggregator and enumerator.                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.1                |
| 16 | 1.1                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.1                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### intarray

[intarray](https://www.postgresql.org/docs/current/intarray.html) provides functions, operators, and index support for 1-D arrays of integers.                                                             

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.5                |
| 16 | 1.5                 |
| 15 | 1.5                 |
| 14 | 1.5                 |
| 13 | 1.3                 |
| 12 | 1.2                 |
| 11 | 1.2                |



### isn

[isn](https://www.postgresql.org/docs/current/isn.html) provides data types for international product numbering standards.                                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.2                |



### lo

[lo](https://www.postgresql.org/docs/current/lo.html) provides data types for international product numbering standards.                                                                                   

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.1                |
| 16 | 1.1                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.1                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### login_hook

[login_hook](https://github.com/splendiddata/login_hook) is a hook to execute `login_hook.login()` at login time.                                                                                          

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.5                |
| 16 | 1.5                 |
| 15 | 1.4                 |
| 14 | 1.4                 |
| 13 | 1.4                 |
| 12 | 1.4                 |
| 11 | 1.4                |



### ltree

[ltree](https://www.postgresql.org/docs/current/ltree.html) is a data type for hierarchical tree-like structures.                                                                                          

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.3                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### oracle_fdw

[oracle_fdw](https://github.com/laurenz/oracle_fdw) is a foreign data wrapper for Oracle databases.                                                                                                        

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | N/A                |



### orafce

[orafce](https://github.com/orafce/orafce) provides functions and operators that emulate a subset of functions and packages from the Oracle RDBMS.                                                         

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 4.9                |
| 16 | 4.4                 |
| 15 | 3.24                |
| 14 | 3.18                |
| 13 | 3.18                |
| 12 | 3.18                |
| 11 | 3.7                |



### pageinspect

[pageinspect](https://www.postgresql.org/docs/current/pageinspect.html) inspects the contents of database pages at a low level.                                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.12               |
| 16 | 1.12                |
| 15 | 1.11                |
| 14 | 1.9                 |
| 13 | 1.8                 |
| 12 | 1.7                 |
| 11 | 1.7                |



### pgaudit

[pgaudit](https://www.pgaudit.org/) provides auditing functionality.                                                                                                                                       

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 16.0 <sup>1</sup>  |
| 16 | 16.0 <sup>1</sup>   |
| 15 | 1.7 <sup>1</sup>    |
| 14 | 1.6.2 <sup>1</sup>  |
| 13 | 1.5 <sup>1</sup>    |
| 12 | 1.4.3 <sup>1</sup>  |
| 11 | 1.3.2 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### pg_buffercache

[pg_buffercache](https://www.postgresql.org/docs/current/pgbuffercache.html) examines the shared buffer cache.                                                                                             

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.5                |
| 16 | 1.4                 |
| 15 | 1.3                 |
| 14 | 1.3                 |
| 13 | 1.3                 |
| 12 | 1.3                 |
| 11 | 1.3                |

> [!NOTE]
> Read the special considerations for extension [pg_buffercache](../concepts-extensions-considerations.md#pg_buffercache) in Flexible Server.


### pg_cron

[pg_cron](https://github.com/citusdata/pg_cron) is a job scheduler for PostgreSQL.                                                                                                                         

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.6 <sup>1</sup>   |
| 16 | 1.6 <sup>1</sup>    |
| 15 | 1.6 <sup>1</sup>    |
| 14 | 1.6 <sup>1</sup>    |
| 13 | 1.6 <sup>1</sup>    |
| 12 | 1.6 <sup>1</sup>    |
| 11 | 1.4-1 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter. 
> [!NOTE]
> Read the special considerations for extension [pg_cron](../concepts-extensions-considerations.md#pg_cron) in Flexible Server.


### pgcrypto

[pgcrypto](https://www.postgresql.org/docs/current/pgcrypto.html) provides cryptographic functions.                                                                                                        

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.3                |
| 16 | 1.3                 |
| 15 | 1.3                 |
| 14 | 1.3                 |
| 13 | 1.3                 |
| 12 | 1.3                 |
| 11 | 1.3                |



### pg_failover_slots

[pg_failover_slots](https://github.com/EnterpriseDB/pg_failover_slots) is a logical replication slot manager for failover purposes.                                                                        

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | N/A                |
| 16 | 1.0.1 <sup>1</sup>  |
| 15 | 1.0.1 <sup>1</sup>  |
| 14 | 1.0.1 <sup>1</sup>  |
| 13 | 1.0.1 <sup>1</sup>  |
| 12 | 1.0.1 <sup>1</sup>  |
| 11 | 1.0.1 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter. 
> [!NOTE]
> Read the special considerations for extension [pg_failover_slots](../concepts-extensions-considerations.md#pg_failover_slots) in Flexible Server.


### pg_freespacemap

[pg_freespacemap](https://www.postgresql.org/docs/current/pgfreespacemap.html) examines the free space map (FSM).                                                                                          

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.2                |



### pg_hint_plan

[pg_hint_plan](https://github.com/ossc-db/pg_hint_plan) makes it possible to tweak PostgreSQL execution plans using so-called hints in SQL comments.                                                       

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.7.0 <sup>1</sup> |
| 16 | 1.6.0 <sup>1</sup>  |
| 15 | 1.5 <sup>1</sup>    |
| 14 | 1.4 <sup>1</sup>    |
| 13 | 1.3.7 <sup>1</sup>  |
| 12 | 1.3.7 <sup>1</sup>  |
| 11 | 1.3.7 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter. 
> [!NOTE]
> Read the special considerations for extension [pg_hint_plan](../concepts-extensions-considerations.md#pg_hint_plan) in Flexible Server.


### pglogical

[pglogical](https://github.com/2ndQuadrant/pglogical) manages PostgreSQL Logical Replication.                                                                                                              

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 2.4.5 <sup>1</sup> |
| 16 | 2.4.4 <sup>1</sup>  |
| 15 | 2.4.2 <sup>1</sup>  |
| 14 | 2.4.1 <sup>1</sup>  |
| 13 | 2.4.1 <sup>1</sup>  |
| 12 | 2.4.1 <sup>1</sup>  |
| 11 | 2.4.1 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### pg_partman

[pg_partman](https://github.com/pgpartman/pg_partman) manages partitioned tables by time or ID.                                                                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 5.0.1 <sup>1</sup> |
| 16 | 5.0.1 <sup>1</sup>  |
| 15 | 4.7.1 <sup>1</sup>  |
| 14 | 4.6.1 <sup>1</sup>  |
| 13 | 4.5.0 <sup>1</sup>  |
| 12 | 4.5.0 <sup>1</sup>  |
| 11 | 4.5.0 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### pg_prewarm

[pg_prewarm](https://www.postgresql.org/docs/current/pgprewarm.html) prewarms the cache with relation data.                                                                                                

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2 <sup>1</sup>   |
| 16 | 1.2 <sup>1</sup>    |
| 15 | 1.2 <sup>1</sup>    |
| 14 | 1.2 <sup>1</sup>    |
| 13 | 1.2 <sup>1</sup>    |
| 12 | 1.2 <sup>1</sup>    |
| 11 | 1.2 <sup>1</sup>   |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter. 
> [!NOTE]
> Read the special considerations for extension [pg_prewarm](../concepts-extensions-considerations.md#pg_prewarm) in Flexible Server.


### pg_repack

[pg_repack](https://reorg.github.io/pg_repack/) reorganizes tables in PostgreSQL databases with minimal locks.                                                                                             

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.4.7              |
| 16 | 1.4.7               |
| 15 | 1.4.7               |
| 14 | 1.4.7               |
| 13 | 1.4.7               |
| 12 | 1.4.7               |
| 11 | 1.4.7              |

> [!NOTE]
> Read the special considerations for extension [pg_repack](../concepts-extensions-considerations.md#pg_repack) in Flexible Server.


### pgrouting

[pgrouting](https://pgrouting.org/) provides geospatial routing functionality.                                                                                                                             

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | N/A                |
| 16 | N/A                 |
| 15 | 3.5.0               |
| 14 | 3.3.0               |
| 13 | 3.3.0               |
| 12 | 3.3.0               |
| 11 | 3.3.0              |



### pgrowlocks

[pgrowlocks](https://www.postgresql.org/docs/current/pgrowlocks.html) shows row-level locking information.                                                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.2                |



### pg_squeeze

[pg_squeeze](https://github.com/cybertec-postgresql/pg_squeeze) removes unused space from a relation.                                                                                                      

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.7 <sup>1</sup>   |
| 16 | 1.6 <sup>1</sup>    |
| 15 | 1.6 <sup>1</sup>    |
| 14 | 1.5 <sup>1</sup>    |
| 13 | 1.5 <sup>1</sup>    |
| 12 | 1.5 <sup>1</sup>    |
| 11 | 1.5 <sup>1</sup>   |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### pg_stat_statements

[pg_stat_statements](https://www.postgresql.org/docs/current/pgstatstatements.html) tracks execution statistics of all SQL statements executed.                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.11 <sup>1</sup>  |
| 16 | 1.10 <sup>1</sup>   |
| 15 | 1.10 <sup>1</sup>   |
| 14 | 1.9 <sup>1</sup>    |
| 13 | 1.8 <sup>1</sup>    |
| 12 | 1.7 <sup>1</sup>    |
| 11 | 1.6 <sup>1</sup>   |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter. 
> [!NOTE]
> Read the special considerations for extension [pg_stat_statements](../concepts-extensions-considerations.md#pg_stat_statements) in Flexible Server.


### pgstattuple

[pgstattuple](https://www.postgresql.org/docs/current/pgstattuple.html) shows tuple-level statistics.                                                                                                      

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.5                |
| 16 | 1.5                 |
| 15 | 1.5                 |
| 14 | 1.5                 |
| 13 | 1.5                 |
| 12 | 1.5                 |
| 11 | 1.5                |

> [!NOTE]
> Read the special considerations for extension [pgstattuple](../concepts-extensions-considerations.md#pgstattuple) in Flexible Server.


### pg_trgm

[pg_trgm](https://www.postgresql.org/docs/current/pgtrgm.html) provides text similarity measurement and index searching based on trigrams.                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.6                |
| 16 | 1.6                 |
| 15 | 1.6                 |
| 14 | 1.6                 |
| 13 | 1.5                 |
| 12 | 1.4                 |
| 11 | 1.4                |



### pg_visibility

[pg_visibility](https://www.postgresql.org/docs/current/pgvisibility.html) examines the visibility map and page-level visibility info.                                                                     

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.2                |



### plpgsql

[plpgsql](https://www.postgresql.org/docs/current/plpgsql.html) pL/pgSQL is a SQL procedural language.                                                                                                     

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### plv8

[plv8](https://github.com/plv8/plv8) pL/JavaScript (v8) is a trusted procedural language.                                                                                                                  

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.1.7              |
| 16 | 3.1.7               |
| 15 | 3.1.7               |
| 14 | 3.0.0               |
| 13 | 3.0.0               |
| 12 | 3.0.0               |
| 11 | 3.0.0              |



### postgis

[postgis](https://www.postgis.net/) geometry and geography spatial types and functions.                                                                                                                    

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### postgis_raster

[postgis_raster](https://www.postgis.net) raster types and functions.                                                                                                                                      

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### postgis_sfcgal

[postgis_sfcgal](https://www.postgis.net) sFCGAL functions.                                                                                                                                                

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### postgis_tiger_geocoder

[postgis_tiger_geocoder](https://www.postgis.net) tiger geocoder and reverse geocoder.                                                                                                                     

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### postgis_topology

[postgis_topology](https://postgis.net/docs/Topology.html) spatial types and functions.                                                                                                                    

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.5.0              |
| 16 | 3.3.3               |
| 15 | 3.3.1               |
| 14 | 3.2.3               |
| 13 | 3.2.3               |
| 12 | 3.2.3               |
| 11 | 3.2.3              |



### postgres_fdw

[postgres_fdw](https://www.postgresql.org/docs/current/postgres-fdw.html) is a foreign-data wrapper for remote PostgreSQL servers.                                                                         

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.1                |
| 16 | 1.1                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |

> [!NOTE]
> Read the special considerations for extension [postgres_fdw](../concepts-extensions-considerations.md#postgres_fdw) in Flexible Server.


### postgres_protobuf

[postgres_protobuf](https://github.com/mpartel/postgres-protobuf) provides protocol buffers for PostgreSQL.                                                                                                

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 0.2                |
| 16 | 0.2                 |
| 15 | 0.2                 |
| 14 | 0.2                 |
| 13 | 0.2                 |
| 12 | 0.2                 |
| 11 | N/A                |



### semver

[semver](https://pgxn.org/dist/semver/doc/semver.html) provides a semantic version data type.                                                                                                              

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 0.32.1             |
| 16 | 0.32.1              |
| 15 | 0.32.0              |
| 14 | 0.32.0              |
| 13 | 0.32.0              |
| 12 | 0.32.0              |
| 11 | 0.32.0             |



### session_variable

[session_variable](https://github.com/splendiddata/session_variable) provides registration and manipulation of session variables and constants.                                                            

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 3.3                |
| 16 | 3.3                 |
| 15 | 3.3                 |
| 14 | 3.3                 |
| 13 | 3.3                 |
| 12 | 3.3                 |
| 11 | 3.3                |



### sslinfo

[sslinfo](https://www.postgresql.org/docs/current/sslinfo.html) provides information about SSL certificates.                                                                                               

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.2                |
| 16 | 1.2                 |
| 15 | 1.2                 |
| 14 | 1.2                 |
| 13 | 1.2                 |
| 12 | 1.2                 |
| 11 | 1.2                |



### tablefunc

[tablefunc](https://www.postgresql.org/docs/current/tablefunc.html) provides functions that manipulate whole tables, including crosstab.                                                                   

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### tds_fdw

[tds_fdw](https://github.com/tds-fdw/tds_fdw) is a foreign data wrapper for querying a TDS database (SAP ASE or SQL Server).                                                                               

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 2.0.3              |
| 16 | 2.0.3               |
| 15 | 2.0.3               |
| 14 | 2.0.3               |
| 13 | 2.0.3               |
| 12 | 2.0.3               |
| 11 | 2.0.3              |



### timescaledb

[timescaledb](https://github.com/timescale/timescaledb) enables scalable inserts and complex queries for time-series data.                                                                                 

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | N/A                |
| 16 | 2.13.0 <sup>1</sup> |
| 15 | 2.10.0 <sup>1</sup> |
| 14 | 2.10.0 <sup>1</sup> |
| 13 | 2.10.0 <sup>1</sup> |
| 12 | 2.10.0 <sup>1</sup> |
| 11 | 1.7.4 <sup>1</sup> |

<sup>1</sup> Enable corresponding libraries in the `shared_preload_libraries` server parameter.

### tsm_system_rows

[tsm_system_rows](https://www.postgresql.org/docs/13/tsm-system-rows.html) is a `TABLESAMPLE` method which accepts number of rows as a limit.                                                              

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### tsm_system_time

[tsm_system_time](https://www.postgresql.org/docs/current/tsm-system-time.html) is a `TABLESAMPLE` method which accepts time in milliseconds as a limit.                                                   

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.0                |
| 16 | 1.0                 |
| 15 | 1.0                 |
| 14 | 1.0                 |
| 13 | 1.0                 |
| 12 | 1.0                 |
| 11 | 1.0                |



### unaccent

[unaccent](https://www.postgresql.org/docs/current/unaccent.html) provides a text search dictionary that removes accents.                                                                                  

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.1                |
| 16 | 1.1                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.1                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### uuid-ossp

[uuid-ossp](https://www.postgresql.org/docs/current/uuid-ossp.html) generates universally unique identifiers (UUIDs).                                                                                      

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 1.1                |
| 16 | 1.1                 |
| 15 | 1.1                 |
| 14 | 1.1                 |
| 13 | 1.1                 |
| 12 | 1.1                 |
| 11 | 1.1                |



### vector

[vector](https://github.com/pgvector/pgvector) is a vector data type and `ivfflat` and `hnsw` access methods.                                                                                              

| PostgreSQL version | Extension version |
| --- | --- |
| 17 | 0.7.0              |
| 16 | 0.7.0               |
| 15 | 0.7.0               |
| 14 | 0.7.0               |
| 13 | 0.7.0               |
| 12 | 0.7.0               |
| 11 | 0.5.1              |



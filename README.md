# Relevant Reseach work

**Leslie Lamport's paper on Byzantine Generals problem**\
This paper gives a background into distributed consensus. This is one of the most fundamental problems in distributed systems due to the unreliable nature of the network.\
https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf

**Google's Bigtable paper [2006]**\
Distributed Key value storage system\
https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf

**Amazon's Dynamo paper [2007]**\
Eventually consistent but highly available, distributed key value storage system\
https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf

**Calvin**\
Transactions in a distributed database\
http://cs-www.cs.yale.edu/homes/dna/papers/calvin-sigmod12.pdf

**Spanner**\
Distributed Relational database using time to achieve 100% CAP\
https://storage.googleapis.com/pub-tools-public-publication-data/pdf/65b514eda12d025585183a641b5a9e096a3c4be5.pdf

## Side reads
**On Gossip protocol**\
Limitations of Gossip protocol. Not everything can (or should) be gossiped, and this paper covers these tradeoffs.\
https://www.cs.cornell.edu/projects/Quicksilver/public_pdfs/2007PromiseAndLimitations.pdf

**C-Store**\
Implementation of typical functions of a database in a read optimized system\
http://db.lcs.mit.edu/projects/cstore/vldb.pdf (http://db.lcs.mit.edu/projects/cstore/)

**Performance Tradeoffs in Read optimized databases**\
Columnar stores and understanding the limitations of write\
http://db.lcs.mit.edu/projects/cstore/VLDB06.pdf

## Interesting Implementations
**Umbra: A Disk-Based System with In-Memory Performance**\
ACID-compliant database built for in-memory analytics speed. For out-of-core processing it falls back gracefully to flash-based storage. Featuring fast code generation, low-latency query execution, and drop-in PostgreSQL compatibility. \
http://cidrdb.org/cidr2020/papers/p29-neumann-cidr20.pdf

## Online Course
Advanced DBMS from Andy Pavlov from CMU\
https://www.youtube.com/watch?v=MM0J0_LX8cg&t=0s&list=PLSE8ODhjZXjYplQRUlrgQKwIAV3es0U6t&index=5

Big Data Made Easy
==================
A list of frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff. Those most frequently used or well-know items are not listed here, which could be referred from awesome series:
[Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) by [Onur Akpolat](https://github.com/onurakpolat) and [The Big-Data Ecosystem Table](https://github.com/zenkay/bigdata-ecosystem/) by [Andrea Mostosi](https://github.com/zenkay) .


## Projects

- [Storage Design and Data Structures](#storage-design-and-data-structures)
- [Distributed System](#distributed-system)
- [Concurrency](#concurrency)
- [Compression](#compression)
- [System Performance and Profiling](#system-performance-and-profiling)
- [Search Engine and Information Retrieval](#search-engine-and-information-retrieval)
- [Large Scale Machine Learning](#large-scale-machine-learning)

###Storage Design and Data Structures
* [Db-readings](https://github.com/rxin/db-readings/) - Readings in Databases .
* [Bitvector](https://github.com/nicola-gigante/bitvector/) - A C++ container-like data structure for storing a vector of bits with fast appending on both sides and fast insertion in the middle, all in succinct space .
* [BitSliceIndex](https://github.com/lemire/BitSliceIndex/) - Experiments on bit-slice indexing .
* [RoaringBitmap](https://github.com/lemire/RoaringBitmap/) - Roaring Bitmap .
* [Cpp-btree](https://code.google.com/p/cpp-btree/) - C++ in-memory containers based on a B-tree data structure.
* [Graphillion](https://github.com/takemaru/graphillion/) - Fast, lightweight graphset operation library .
* [Emphf](https://github.com/ot/emphf/) - An efficient external-memory algorithm for the construction of minimal perfect hash functions .
* [Splay Map](https://github.com/grubino/splay_map/) - STL map implemented with splay tree .
* [Cedar](http://www.tkl.iis.u-tokyo.ac.jp/~ynaga/cedar/) - C++ implementation of efficiently-updatable double-array trie .
* [WikiSort](https://github.com/BonzaiThePenguin/WikiSort/) - Fast and stable sort algorithm that uses O(1) memory. Public domain .
* [Annoy](https://github.com/spotify/annoy/) - Approximate Nearest Neighbors in C++/Python optimized for memory usage and loading/saving to disk .
* [Expgram](https://github.com/tarowatanabe/expgram/) - An ngram toolkit with succinct storage .
* [Cuckoofilter](https://github.com/efficient/cuckoofilter/) - A Bloom filter replacement for approximated set-membership queries .
* [PackedArray](https://github.com/gpakosz/PackedArray/) - Random access array of tightly packed unsigned integers .
* [FFBF](https://github.com/efficient/ffbf/) - Feed-forward Bloom filters .
* [Concurrent Trees](https://github.com/wichtounet/btrees/) - C++ implementation of concurrent Binary Search Trees .
* [Concurrent B-Tree](https://github.com/malbrain/Btree-source-code/) - A working project for High-concurrency B-tree source code in C .
* [Block-graph](https://github.com/choobin/block-graph/) - A succinct implementation of a block-graph data structure .
* [RePair-WaveletTree-Graph](https://github.com/nilehmann/RePair-WaveletTree-Graph/) - Graph Implementation with repair bitmap compressed WaveletTree .
* [RLZ](https://github.com/skuruppu/RLZ/) - Contains the RLZ compression and self-index source code .
* [Serangequerying](http://lbd.udc.es/research/serangequerying/) - Space-Efficient Structures for Range Querying .
* [Succinct](https://github.com/ahartik/succinct/) - Experimentation with various succinct data structures. Combines previous doc-counter and wavelet-tree repos .
* [Sdsl-lite](https://github.com/simongog/sdsl-lite/) - Succinct Data Structure Library 2.0 .
* [Relative-FMIndex](https://github.com/jltsiren/relative-fm/) - Relative FM-index which is smaller but slower than plain FMIndex.
* [GCSA](https://github.com/jltsiren/gcsa2/) - Generalized Compressed Suffix Array.
* [Succinct](https://github.com/ot/succinct/) - A collection of succinct data structures .
* [Rmq](https://github.com/leifwalsh/rmq/) - Implementations of LCA and RMQ data structures from "The LCA Problem Revisited" .
* [YuNomi](https://github.com/jnory/YuNomi/) - Compressed Array Library .
* [DACs](http://lbd.udc.es/research/DACS/) - Directly Addressable Codes (DACs) consist in a variable-length encoding scheme for integers that enables direct access to any element of the encoded sequence and obtains compact spaces .
* [Cpi00](https://code.google.com/p/cpi00/) - The compressed permuterm index .
* [Smbt](https://code.google.com/p/smbt/) - Succinct Multibit Tree for similarity search .
* [Gwt](https://code.google.com/p/gwt/) - Graph-indexing wavelet tree for graph similarity search .
* [Webgraphs](http://webgraphs.recoded.cl/) - Fast and Compact Web Graph Representations .
* [Erika-trie ](https://code.google.com/p/erika-trie/) - Erika-trie: succinct trie library .
* [Path_decomposed_tries](https://github.com/ot/path_decomposed_tries/) - Implementation of the data structures described in the paper "Fast Compressed Tries using Path Decomposition" .
* [Sumire-tries](https://code.google.com/p/sumire-tries/) - A variety of succinct tries .
* [Trie4j](https://github.com/takawitter/trie4j/) - (Succinct) trie implementation in Java .
* [SuDS](http://www.cs.helsinki.fi/group/suds/) - Succinct Data Structures (SuDS) www.cs.helsinki.fi .
* [Marisa-trie](https://code.google.com/p/marisa-trie/) - Marisa succinct trie .
* [LibCDS](https://github.com/fclaude/libcds2/) - Compact Data Structures Library .
* [HSDS](https://github.com/hideo55/cpp-HSDS/) - Succinct Data Structure Library Collection.Includes bit-vector/wavelet-matrix/trie .
* [BWTIL](https://github.com/nicolaprezza/BWTIL/) - BWT Text Indexing Library: a set of tools to work with BWT-based text indexes .
* [Hip-hyperloglog](https://github.com/iwiwi/hip-hyperloglog/) - C++ implementation of an approximate distinct counter by HIP estimator on HyperLogLog .
* [Gonzalo Navarro](http://www.dcc.uchile.cl/~gnavarro/publ.html) - Publications of Gonzalo Navarro .
* [Kvtx](https://github.com/kumagi/kvtx/) - Transaction over CAS see https://docs.google.com/open?id=0B04zCRiCIQGGZDcyNTEwZGQtODk4Yy00NjEwLWI1MjQtYjc3NzJhN2RlNzk0  .
* [Fatcache](https://github.com/twitter/fatcache/) - Memcache on SSD .
* [WiredTiger](https://github.com/wiredtiger/wiredtiger/) - WiredTiger's source tree http://source.wiredtiger.com/ .
* [FD-Tree](http://pages.cs.wisc.edu/~yinan/fdtree.html/) - FD-Tree: a Tree Index on Solid State Drives .
* [Silo](https://github.com/stephentu/silo/) - Multicore in-memory storage engine .
* [MemC3](https://github.com/efficient/memc3/) - An in-memory key-value cache based on concurrent cuckoo hashing.
* [Libart](https://github.com/armon/libart/) - Adaptive Radix Trees implemented in C .
* [Masstree](https://github.com/kohler/masstree-beta/) - Masstree, a fast, multi-core key-value store .
* [NVMKV](https://github.com/opennvm/nvmkv/) - NVM key-value store API lIbrary repository. http://opennvm.github.io/nvmkv-documents/ .
* [HYRISE](https://github.com/hyrise/hyrise/) - In-Memory Hybrid Storage Engine .
* [HyPer](http://hyper-db.de/) - A hybrid online transactional processing (OLTP) and online analytical processing (OLAP) high-performance main memory database system that is optimized for modern hardware .
* [NoVoHT](https://github.com/kev40293/NoVoHT/) - NoVoHT: a Lightweight Dynamic Persistent NoSQL Key/Value Store on NVRAM .
* [HERD](https://github.com/efficient/HERD/) - A Highly Efficient key-value system for RDMA .
* [Cayley](https://github.com/google/cayley/) - An open-source graph database .
* [Forestdb](https://github.com/couchbaselabs/forestdb/) - A Fast Key-Value Storage Engine Based on Hierarchical B+-Tree Trie .
* [Mdbm](https://github.com/yahoo/mdbm/) - A very fast memory-mapped key/value store by Yahoo .
* [Nldb](https://github.com/Nanolat/nldb/) - Nanolat Database supporting 1M transactions per second .
* [Weaver](https://github.com/dubey/weaver/) - A scalable, fast, consistent graph store http://weaver.systems .
* [FastBit_UDF](https://github.com/greenlion/FastBit_UDF/) -  MySQL UDF for creating, manipulating and querying FastBit indexes .
* [Jump Consistent Hash](https://github.com/anachronistic/jump-consistent-hash/) -  A Go implementation of the jump consistent hash .
* [Content Defined Chunking](https://moinakg.wordpress.com/2013/06/22/high-performance-content-defined-chunking/) -  High Performance Content Defined Chunking .
* [SSD optimizations](http://www.nodalink.com/blog_SSD_random_io_optimization_26_01_2014.html/) - Optimizing SSDs random IOPs, noop/tpps scheduler, rotational=0, add_random=0 .
* [Article-SSD](http://codecapsule.com/2014/02/12/coding-for-ssds-part-6-a-summary-what-every-programmer-should-know-about-solid-state-drives//) - Coding for SSDs - What every programmer should know about solid-state drives .
* [Article-Key-Value](http://codecapsule.com/2013/05/13/implementing-a-key-value-store-part-5-hash-table-implementations/) - Implementing a Key-Value Store .
* [Article-MVCC](http://highlyscalable.wordpress.com/2012/01/07/mvcc-transactions-key-value/) - Implementation of MVCC Transactions for Key-Value Stores .
* [Article-SSD](http://arstechnica.com/information-technology/2012/06/inside-the-ssd-revolution-how-solid-state-disks-really-work/) - Solid-state revolution: in-depth on how SSDs really work .
* [Dexter](https://wwwdb.inf.tu-dresden.de/research-projects/projects/dexter/) - Dexter database research group .
* [Streaminer](https://github.com/mayconbordin/streaminer/) - A collection of algorithms for mining data streams http://mayconbordin.github.io/streaminer/ .
* [Article-Art of Approximating](https://metamarkets.com/2013/histograms//) - The Art of Approximating Distributions: Histograms and Quantiles at Scale .
* [Article-Sketch of the Day](http://research.neustar.biz/2013/09/16/sketch-of-the-day-frugal-streaming//) - Sketch of the Day: Frugal Streaming .
* [Article-Sketch of the Day](http://research.neustar.biz/2012/07/09/sketch-of-the-day-k-minimum-values/) - Sketch of the Day: K-Minimum Values .
* [Article-Sketch of the Day](http://research.neustar.biz/2012/08/20/k-minimum-values-sketching-error-hash-functions-and-you/) - Sketch of the Day: K-Minimum Values: Sketching Error, Hash Functions, and You .



###Distributed System
* [Pequod](https://github.com/bryankate/pequod/) - A distributed key-value cache with builtin materialized views, see "Easy Freshness with Pequod Cache Joins" .
* [Crate](https://crate.io/) - CRATE: Your Elastic Data Store .
* [Elliptics](https://github.com/reverbrain/elliptics/) - Distributed hashtable storage .
* [Mcrouter](https://github.com/facebook/mcrouter/) - Mcrouter is a memcached protocol router for scaling memcached deployments .
* [Codis](https://github.com/wandoulabs/codis/) - Yet another fast distributed solution for Redis .
* [zBase](https://github.com/zbase/) - A high-performance, elastic, distributed key-value store .
* [Dynomite](https://github.com/Netflix/dynomite/) - A generic dynamo implementation for different k-v storage engines .
* [AsterixDB](https://asterixdb.ics.uci.edu/) - Full-function BDMS (Big Data Management System) .
* [RAMCloud](https://ramcloud.atlassian.net/wiki/display/RAM/RAMCloud/) - A new class of storage for large-scale datacenter applications. It is a key-value store that keeps all data in DRAM at all times .
* [Cockroach](https://github.com/cockroachdb/cockroach/) - A Scalable, Geo-Replicated, Transactional Datastore .
* [Seaweed-FS](https://github.com/chrislusf/weed-fs/) - A simple and highly scalable distributed file system. There are two objectives: to store billions of files! to serve the files fast .
* [InfiniSQL](http://www.infinisql.org/) - InfiniSQL is the database for always on, rapid growth applications that need to collect and analyze in real time--even for complex transactions .
* [Druid](https://github.com/metamx/druid/) - Real²time Exploratory Analytics on Large Datasets http://druid.io .
* [Wasp](https://github.com/alibaba/wasp/) - A megastore-like system http://alibaba.github.io/wasp/ .
* [Haeinsa](https://github.com/VCNC/haeinsa) - linearly scalable multi-row, multi-table transaction library for HBase based on Percolator .
* [Yrmcds](https://github.com/cybozu/yrmcds/) - Memcached compatible KVS with master/slave replication. http://cybozu.github.io/yrmcds/ .
* [3levelmemcache](https://github.com/forcedotcom/3levelmemcache/) - Memcache improvements by Data.com .
* [Vitess](https://github.com/youtube/vitess/) - Vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services .
* [Replicant](https://github.com/rescrv/Replicant/) - A system for maintaining replicated state machines .
* [Skipgraph](https://github.com/kumagi/skipgraph/) - Implementation of skipgraph on messagepack-rpc .
* [Kylin](http://www.kylin.io/) - BigQuery based on Hadoop .
* [Cubert](https://github.com/linkedin/Cubert/) - A fast and efficient batch computation engine for complex analysis and reporting of massive datasets on Hadoop .
* [REEF](http://www.reef-project.org/) - The Retainable Evaluator Execution Framework .
* [Phat](https://github.com/rdadolf/phat/) - An implementation of the Chubby lock service protocol in Msgpack RPC .
* [Hydra](https://github.com/addthis/hydra/) - A distributed data processing and storage system originally developed at AddThis .
* [Hystrix](https://github.com/Netflix/Hystrix/) - A latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable .
* [Nativetask](https://github.com/intel-hadoop/nativetask) - A high performance C++ API & runtime for Hadoop MapReduce .
* [Taskgraph](https://github.com/taskgraph/taskgraph/) -  A fault tolerant, distributed task driven framework written in Go.
* [Summingbird](https://github.com/twitter/summingbird/) - Streaming MapReduce with Scalding and Storm https://twitter.com/summingbird .
* [Hustle](https://github.com/tspurway/hustle/) - A column oriented, embarrassingly distributed relational event database .
* [Embulk](https://github.com/embulk/embulk/) - A plugin-based parallel bulk data loader that makes painful data integration works relaxed .
* [Chronos](http://airbnb.github.io/chronos/) - Chronos: A Replacement for Cron, see http://nerds.airbnb.com/introducing-chronos/ .
* [Tyrant](https://github.com/wandoulabs/tyrant/) - Golang job scheduler based on mesos.
* [Cocaine](http://api.yandex.com/cocaine//) - An open-source PaaS (platform as a service) system for creating custom cloud hosting apps from Yandex .
* [Weave](https://github.com/zettio/weave/) - The Docker Network .
* [Course-CS6452](http://www.cs.cornell.edu/courses/cs6452/2012sp/lectures.php/) - Datacenter Networks and Services .
* [Article-Service Discovery](http://jasonwilder.com/blog/2014/02/04/service-discovery-in-the-cloud/) - Open-Source Service Discovery - Jason Wilder's Blog jasonwilder.com  .
* [Article-Replication and Latency consistency tradeoff](http://dbmsmusings.blogspot.com/2011/12/replication-and-latency-consistency.html/) - Replication and the latency-consistency tradeoff  .

###Concurrency
* [Concurrent Queue](https://github.com/cameron314/concurrentqueue/) - A fast multiple-producer, multi-consumer lock-free concurrent queue for C++11 .
* [CAF](http://actor-framework.org/) - An Open Source Implementation of the Actor Model in C++ .
* [TAMER](https://github.com/kohler/tamer/) - C++ extensions for readable event-driven programming .
* [C++React](https://github.com/schlangster/cpp.react/) - A reactive programming library for C++11 .
* [Libslock](https://github.com/tudordavid/libslock/) - Cross-platform atomic operations and lock algorithm library http://lpd.epfl.ch/site/ssync .
* [CDS](https://github.com/avis/cds/) - Header only C++ Concurrent Data Structures library .
* [Libcds](http://libcds.sourceforge.net/) - A C++ template library of lock-free and fine-grained algorithms .
* [Locksmith](https://github.com/cmccabe/lksmith/) - A library for debugging locking in C, C++, or Objective C programs .
* [Concurrency-concepts](https://github.com/kaisellgren/Concurrency-concepts/) - A guide to concurrency, multi-threading and parallel programming concepts. Explains the differences between every concept, their advantages and disadvantages in detail .
* [Concurrency Kit](http://concurrencykit.org/) - Concurrency primitives, safe memory reclamation mechanisms and non-blocking data structures for the research, design and implementation of high performance concurrent systems .
* [Nanahan](https://github.com/kumagi/nanahan/) - An implementation of Hopscotch hashing for single thread .
* [Scalex](https://github.com/stephentu/scalex/) - Code snippets for the workshop on concurrent data structure implementation .
* [CBB](http://amino-cbbs.sourceforge.net/) - Provides a set of concurrent building blocks (Java & C/C++) that can be used to develop parallel/multi-threaded applications .
* [Thrust](https://github.com/thrust/thrust/) - A parallel algorithms library which resembles the C++ Standard Template Library (STL) .
* [Varon-t](https://github.com/redjack/varon-t/) - A C implementation of Disruptor queues http://varon-t.readthedocs.org/ .
* [disruptor--](https://github.com/fsaintjacques/disruptor--/) - Disruptor concurency pattern in c++ .
* [Lockfree Queue](https://github.com/krizhanovsky/NatSys-Lab/blob/master/lockfree_rb_q.cc/) -  Lock-free Condition Wait for Lock-free Multi-producer Multi-consumer Queue, see http://natsys-lab.blogspot.ru/2013/08/lock-free-condition-wait-for-lock-free.html .
* [Ssmem](https://github.com/LPD-EPFL/ssmem/) - A simple object-based memory allocator with epoch-based garbage collection, the publication "Asynchronized Concurrency: The Secret to Scaling Concurrent Search Data Structures" .
* [CLHT](https://github.com/LPD-EPFL/CLHT/) - A very fast and scalable (lock-based and lock-free) hash table that uses cache-line sized buckets .
* [Comsat](http://www.paralleluniverse.co/comsat/) - Comsat lets your application enjoy the scalability of asynchronous web-frameworks, serving many thousands of concurrent long-lived connections, or issuing hundreds of web-service calls for each request, all while maintaining the simple “thread per request” model .
* [Article-TM](http://kukuruku.co/hub/cpp/transactional-memory-history-and-development/) - Transactional Memory: History and Development .


###Compression
* [Shoco](https://github.com/Ed-von-Schleck/shoco/) - A compressor for small text strings http://ed-von-schleck.github.io/shoco/ .
* [Smaz](https://github.com/antirez/smaz/) - Small strings compression library .
* [Zstandard](https://github.com/Cyan4973/zstd/) - Lossless compression algorithm providing both good compression ratio and speed .
* [Url Compress](https://github.com/kazuho/url_compress/) - A static PPM-based URL compressor / decompressor .
* [Floating-Point](http://www.cs.unc.edu/~isenburg/lcpfpv/) -  Lossless Compression of Predicted Floating-Point Values .


###System Performance And Profiling
* [Vmmlib](http://vmml.github.io/vmmlib/) - A templatized C++ vector and matrix math library .
* [Blaze-lib](https://code.google.com/p/blaze-lib/) - A high performance C++ math library .
* [Light-matrix](https://github.com/lindahua/light-matrix/) - A Light-weight and Fast Template Matrix Library .
* [Light-simd](https://github.com/lindahua/light-simd/) - A light weight library for SIMD based computation .
* [MathSimd](https://github.com/HeliumProject/MathSimd/) - SIMD-optimized math library in C++ .
* [Opti](https://github.com/herumi/opti/) - Experiment of x86/x64 optimization .
* [Fmath](https://github.com/herumi/fmath/) - Fast log and exp functions for x86/x64 SSE http://homepage1.nifty.com/herumi/soft/fmath.html .
* [Mie](https://github.com/herumi/mie/) - Fast string library with SSE4.2 .
* [Libsimdpp](https://github.com/p12tic/libsimdpp/) - Header-only zero-overhead C++ wrapper for SIMD intrinsics of multiple instruction sets .
* [SEQAN](http://www.seqan.de/) - An open source C++ library of efficient algorithms and data structures for the analysis of sequences with the focus on biological data .
* [Fastsocket](https://github.com/fastos/fastsocket/) -  A highly scalable socket and its underlying networking implementation of Linux kernel .
* [Smart](https://github.com/yandex/smart/) - SMT-aware Real-time scheduler for Linux from Yandex.
* [Simple Binary Encoding](http://real-logic.github.io/simple-binary-encoding/) - Serialization with ultra low latency .
* [Libdivide](http://libdivide.com/) - An open source library for optimizing integer division .
* [Farmhash](https://code.google.com/p/farmhash/) - FarmHash is a successor to CityHash, and includes many of the same tricks and techniques, several of them taken from Austin Appleby’s MurmurHash .
* [Proxygen](https://github.com/facebook/proxygen/) - A collection of C++ HTTP libraries including an easy to use HTTP server .
* [Yamail](https://github.com/yandex/yamail/) - YMail General Purpose Library .
* [mTCP](http://shader.kaist.edu/mtcp/) - A Highly Scalable User-level TCP Stack for Multicore Systems .
* [UNetStack](https://github.com/bioothod/unetstack/) - Userspace TCP/IP stack .
* [Ktap](https://github.com/ktap/ktap/) - A lightweight script-based dynamic tracing tool for Linux http://ktap.org .
* [Perfbook](https://www.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html/) - Is Parallel Programming Hard, And, If So, What Can You Do About It ?
* [Article-GC-Java](http://engineering.linkedin.com/garbage-collection/garbage-collection-optimization-high-throughput-and-low-latency-java-applications/) - Garbage Collection Optimization for High-Throughput and Low-Latency Java Applications | LinkedIn Engineering .
* [Article-Memory Management](http://engineering.linkedin.com/performance/optimizing-linux-memory-management-low-latency-high-throughput-databases/) - Optimizing Linux Memory Management for Low-latency / High-throughput Databases | LinkedIn Engineering .
* [Article-Modern Microprocessors](http://www.lighterra.com/papers/modernmicroprocessors/) - Modern Microprocessors A 90 Minute Guide! .
* [Article-Cache Oblivious Array](http://0fps.net/2013/05/28/cache-oblivious-array-operations/) -  Cache oblivious array operations .
* [Article-Understanding Memory](http://www.ualberta.ca/CNS/RESEARCH/LinuxClusters/mem.html/) - Understanding Memory .
* [Article-1975 Programming](https://news.ycombinator.com/item?id=4874304/) - So what's wrong with 1975 programming? .
* [Article-Database Research](http://www.slideshare.net/bart7449/database-research-on-modern-computing-architecture/) - Database Research on Modern Computing Architecture .
* [Article-Linux Learn From Solaris](http://www.slideshare.net/brendangregg/what-linux-can-learn-from-solaris-performance-and-viceversa/) - What Linux can learn from Solaris performance and vice-versa .
* [Brendan D. Gregg](http://www.brendangregg.com/) - Blog of Brendan D. Gregg .
* [Course-CMU 18-645](http://users.ece.cmu.edu/~pueschel/teaching/18-645-CMU-spring08/course.html/) - How to Write Fast Code .
* [ParallelismBook](https://github.com/fengChenHPC/parallelismBook/) - A book about parallel computing & code optimization .
* [Blackhole](https://github.com/3Hren/blackhole/) - Yet another logging library. http://blackhole-logger.herokuapp.com .
* [Handystats](https://github.com/shindo/handystats/) - C++ library for collecting user-defined in-process runtime statistics with low overhead .

###Search Engine and Information Retrieval
* [SF1R](http://github.com/izenecloud/sf1r-lite) - A distributed massive data engine for enterprise/vertical search written in C++ .
* [Partitioned_elias_fano](https://github.com/ot/partitioned_elias_fano/) - Code used for the experiments in the paper "Partitioned Elias-Fano Indexes" .
* [Data Structures for Inverted Indexes](https://github.com/ot/ds2i/) - Optimal Space-Time Tradeoffs for Inverted Indexes .
* [Surf](https://github.com/simongog/surf/) - SUccinct Retrieval Framework .
* [FastPFor](https://github.com/lemire/FastPFor/) - Fast integer compression .
* [Simdcomp](https://github.com/lemire/simdcomp/) - A simple C library for compressing lists of integers .
* [SIMDCompressionAndIntersection](https://github.com/lemire/SIMDCompressionAndIntersection/) - A C++ library to compress and intersect sorted lists of integers using SIMD instructions .
* [TurboPFor](https://github.com/powturbo/TurboPFor/) - Fastest Integer Compression .
* [Pos-cmp](https://github.com/mpetri/pos-cmp/) - Comparison framework for positional inverted indexes and self-index supporting phrase queries .
* [MaskedVByte](https://github.com/lemire/MaskedVByte/) - SIMD-accelerated VByte Compression, Publication "Vectorized VByte Decoding" .
* [Wavelet](https://www.cyberagent.co.jp/recruit/techreport/report/id=8729/) - Information Retrieval based on Wavelet Tree .
* [Shuffla](https://github.com/jaaro/Shuffla/) - Search engine using kd-tree .
* [RoSA](https://github.com/simongog/RoSA/) - Large-Scale Pattern Search Using Reduced-Space On-Disk Suffix Arrays .
* [Dualsorted](https://github.com/yingfeng/dualsorted/) - Dual sorted inverted index based on Wavelet Tree .
* [Treap](https://github.com/yingfeng/treap/) - Faster and Smaller Inverted Indices with Treaps .
* [Gigablast](https://github.com/gigablast/open-source-search-engine/) - A distributed open source search engine and spider written in C/C++ for Linux .
* [Libface](https://github.com/duckduckgo/cpp-libface/) - Fastest auto-complete in the east .
* [SIMD-Based-Posting-lists](https://github.com/maximecaron/SIMD-Based-Posting-lists/) - Implementation of Alexander A. Stepanov inverted Index Compression algorithms .
* [Groonga](http://groonga.org/) - Open-source fulltext search engine and column store .
* [Pastec](https://github.com/Visu4link/pastec/) - An open source index and search engine for image recognition .
* [Enterprise-search](https://github.com/searchdaimon/enterprise-search/) - An open source search engine for corporate data and websites. http://www.searchdaimon.com/ .
* [Verticut](https://github.com/EasonLiao/verticut/) - Image search engine on Infiniband .
* [Atire](http://atire.org/) - A search engine built using the most effective recent research techniques discovered by Information Retrieval researchers around the world .
* [Mg4j](http://mg4j.di.unimi.it/) - Academic search engine with succinct design(say quasi-succinct indices) .
* [Argos](https://github.com/windoze/Argos/) -  A structural data search engine .


###Large Scale Machine Learning
* [LASER](http://github.com/izenecloud/laser/) - A Scalable Response Prediction Platform For Online Advertising .
* [Parameter Server](https://github.com/mli/parameter_server/) - A distributed machine learning framework. http://parameterserver.org .
* [Petuum](http://petuum.github.io/) - A distributed machine learning framework implementing parameter server model .
* [Paracel](http://paracel.io/) - Parameter server by Douban Inc .
* [H2O](http://0xdata.com/h2o/) - Fastest in-memory platform for machine learning and predictive analytics on big data .
* [Oryx](https://github.com/cloudera/oryx/) - Simple real-time large-scale machine learning infrastructure implementing Lambda Architecture .
* [Admm_Allreduce](https://github.com/BaiGang/admm_allreduce/) - ADMM optimizer on Apache Hadoop with allReduce. .
* [Hivemall](https://github.com/myui/hivemall/) - Scalable machine learning library for Hive/Hadoop .
* [Ml-ease](https://github.com/linkedin/ml-ease/) - ADMM based large scale logistic regression .
* [douban_pGBRT](https://github.com/ryaninhust/douban_pGBRT/) - Parallel GBRT from Douban Inc .
* [Parlearn](https://github.com/stephentu/parlearn/) - Parallel SGD implementation .
* [Xgboost](https://github.com/tqchen/xgboost/) - eXtreme Gradient Boosting (Tree) Library .
* [AcroMUSASHI Stream-ML](https://github.com/acromusashi/acromusashi-stream-ml/) - AcroMUSASHI Stream-ML - Machine Learning Library .
* [DIMSUM](https://blog.twitter.com/2014/all-pairs-similarity-via-dimsum/) - All-pairs similarity via DIMSUM .
* [StreamSVM](http://www.r.dl.itc.u-tokyo.ac.jp/~masin/streamsvm.html/) - StreamSVM is the fastest implementation to learn linear SVM with large dataset that cannot fit in memory in your computer .
* [Distributed-liblinear](http://www.csie.ntu.edu.tw/~cjlin/libsvmtools/distributed-liblinear/) - Libraries for Large-scale Linear Classification on Distributed Environments .
* [SparkADMM](https://github.com/jackdreilly/SparkADMM/) - ADMM implementation on Spark Cluster .
* [NOMAD](https://sites.google.com/site/hyokunyun/software/) - Non-locking, stOchastic Multi-machine algorithm for Asynchronous and Decentralized matrix completion .
* [Stream-ml](https://github.com/ddutta/stream-ml/) - Streaming SGD inspired by http://blog.smola.org/post/977927287/parallel-stochastic-gradient-descent .
* [LIBPMF](http://www.cs.utexas.edu/~rofuyu/libpmf/) - A Library for Large-scale Parallel Matrix Factorization .
* [LIBMF](http://www.csie.ntu.edu.tw/~cjlin/libmf/) -  A Matrix-factorization Library for Recommender Systems .
* [KnittingBoar](https://github.com/jpatanooga/KnittingBoar/) - Parallel Iterative Algorithm (SGD) on Hadoop's YARN framework .
* [Trident-ml](https://github.com/pmerienne/trident-ml/) - Trident-ML : A realtime online machine learning library .
* [Mlpack](http://mlpack.org/) - A scalable c++ machine learning library .
* [LASSO](https://github.com/wangkuiyi/lasso/) - A parallel regression model learning system based on MRML.
* [Jubatus](http://jubat.us/) - Distributed Online Machine Learning Framework .
* [Vowpal_Wabbit](https://github.com/JohnLangford/vowpal_wabbit/) - A fast online learning algorithm http://hunch.net/~vw/ .
* [DeepDist](http://deepdist.com/) - Lightning-Fast Deep Learning on Spark via parallel stochastic gradient updates(compared with MLLib) .
* [DMLC](https://github.com/dmlc/) - Distributed (Deep) Machine Learning Common .
* [BIDMach](https://github.com/BIDData/BIDMach/) -  CPU and GPU-accelerated Machine Learning Library in Scala .
* [Spark-Multiboost](https://github.com/BaiGang/spark_multiboost/) -   An implementation of the multi-class/multi-label classifier, of which the training is carried out using AdaBoost.MH on Apache Spark .

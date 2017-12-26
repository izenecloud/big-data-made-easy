AI+BigData+Cloud Made Easy
==================
A list of frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff. Those most frequently used or well-know items are not listed here, which could be referred from awesome series:
[Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) by [Onur Akpolat](https://github.com/onurakpolat) and [The Big-Data Ecosystem Table](https://github.com/zenkay/bigdata-ecosystem/) by [Andrea Mostosi](https://github.com/zenkay) .


## Projects

- [Storage Design and Data Structures](#storage-design-and-data-structures)
- [Distributed Infrastructure for Cloud---Database and Storage](#distributed-storage)
- [Distributed Infrastructure for Cloud---Application](#distributed-application)
- [Distributed Infrastructure for Cloud---A(AI)B(BigData)C(Cloud)](#distributed-abc)
- [Concurrency](#concurrency)
- [System Performance and Profiling](#system-performance-and-profiling)
- [Search Engine and Information Retrieval](#search-engine-and-information-retrieval)


### Storage Design and Data Structures
* [Db-readings](https://github.com/rxin/db-readings/) - Readings in Databases .
* [Bitvector](https://github.com/nicola-gigante/bitvector/) - A C++ container-like data structure for storing a vector of bits with fast appending on both sides and fast insertion in the middle, all in succinct space .
* [BitSliceIndex](https://github.com/lemire/BitSliceIndex/) - Experiments on bit-slice indexing .
* [RoaringBitmap](https://github.com/lemire/RoaringBitmap/) - Roaring Bitmap .
* [Pilosa](https://github.com/pilosa/pilosa/) - High performance OLAP based on roaring bitmap .
* [Cpp-btree](https://code.google.com/p/cpp-btree/) - C++ in-memory containers based on a B-tree data structure.
* [Graphillion](https://github.com/takemaru/graphillion/) - Fast, lightweight graphset operation library .
* [Emphf](https://github.com/ot/emphf/) - An efficient external-memory algorithm for the construction of minimal perfect hash functions .
* [Skipgraph](https://github.com/kumagi/skipgraph/) - Implementation of skipgraph on messagepack-rpc .
* [Splay Map](https://github.com/grubino/splay_map/) - STL map implemented with splay tree .
* [Cedar](http://www.tkl.iis.u-tokyo.ac.jp/~ynaga/cedar/) - C++ implementation of efficiently-updatable double-array trie .
* [WikiSort](https://github.com/BonzaiThePenguin/WikiSort/) - Fast and stable sort algorithm that uses O(1) memory. Public domain .
* [Annoy](https://github.com/spotify/annoy/) - Approximate Nearest Neighbors in C++/Python optimized for memory usage and loading/saving to disk .
* [Expgram](https://github.com/tarowatanabe/expgram/) - An ngram toolkit with succinct storage .
* [Cuckoofilter](https://github.com/efficient/cuckoofilter/) - A Bloom filter replacement for approximated set-membership queries .
* [DCF](https://github.com/CGCL-codes/DCF/) - Dynamic Cuckoo Filter .
* [PackedArray](https://github.com/gpakosz/PackedArray/) - Random access array of tightly packed unsigned integers .
* [FrameOfReference](https://github.com/lemire/FrameOfRefence/) - C++ library to pack and unpack vectors of integers having a small range of values using a technique called Frame of Reference .
* [FFBF](https://github.com/efficient/ffbf/) - Feed-forward Bloom filters .
* [Concurrent Trees](https://github.com/wichtounet/btrees/) - C++ implementation of concurrent Binary Search Trees .
* [Concurrent B-Tree](https://github.com/malbrain/Btree-source-code/) - A working project for High-concurrency B-tree source code in C .
* [Palmtree](https://github.com/runshenzhu/palmtree/) - An implementation of Intel's concurrent B+Tree (Palm Tree) .
* [BwTree](https://github.com/wangziqi2013/BwTree/) -  An open sourced implementation of Bw-Tree in SQL Server Hekaton .
* [W-TinyLFU](https://github.com/mandreyel/w-tinylfu/) - C++11 header-only implementation for Window-TinyLFU Cache .
* [Block-graph](https://github.com/choobin/block-graph/) - A succinct implementation of a block-graph data structure .
* [RePair-WaveletTree-Graph](https://github.com/nilehmann/RePair-WaveletTree-Graph/) - Graph Implementation with repair bitmap compressed WaveletTree .
* [RLZ](https://github.com/skuruppu/RLZ/) - Contains the RLZ compression and self-index source code .
* [Serangequerying](http://lbd.udc.es/research/serangequerying/) - Space-Efficient Structures for Range Querying .
* [Succinct](https://github.com/ahartik/succinct/) - Experimentation with various succinct data structures. Combines previous doc-counter and wavelet-tree repos .
* [Sdsl-lite](https://github.com/simongog/sdsl-lite/) - Succinct Data Structure Library 2.0 .
* [Relative-FMIndex](https://github.com/jltsiren/relative-fm/) - Relative FM-index which is smaller but slower than plain FMIndex.
* [GCSA](https://github.com/jltsiren/gcsa2/) - Generalized Compressed Suffix Array.
* [Succinct](https://github.com/ot/succinct/) - A collection of succinct data structures .
* [DYNAMIC](https://github.com/xxsds/DYNAMIC/) - Dynamic succinct/compressed data structures .
* [DPT](https://github.com/kurpicz/dpt/) - Distributed Patricia Trie .
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
* [HSDS](https://github.com/hideo55/cpp-HSDS/) - Succinct Data Structure Library Collection including bit-vector/wavelet-matrix/trie .
* [BWTIL](https://github.com/nicolaprezza/BWTIL/) - BWT Text Indexing Library: a set of tools to work with BWT-based text indexes .
* [Bwt-Merge](https://github.com/jltsiren/bwt-merge/) - A tool for merging large BWTs .
* [PWT](https://github.com/kurpicz/pwm/) - Parallel Wavelet Tree and Wavelet Matrix Construction .
* [PSAC](https://github.com/patflick/psac/) - Parallel Suffix Array, LCP Array, and Suffix Tree Construction .
* [R-Index](https://github.com/nicolaprezza/r-index/) - Optimal space run-length Burrows-Wheeler transform full-text index  .
* [Fbcsa](https://github.com/mranisz/fbcsa/) - Fixed Block based Compact Suffix Array  .
* [Quantile-Index](https://github.com/kit-susi/quantile-index/) - Code for "The Quantile Index -- Succinct Self-Index for Top-k Document Retrieval" .
* [Gonzalo Navarro](http://www.dcc.uchile.cl/~gnavarro/publ.html) - Publications of Gonzalo Navarro .
* [Kvtx](https://github.com/kumagi/kvtx/) - Transaction over CAS see https://docs.google.com/open?id=0B04zCRiCIQGGZDcyNTEwZGQtODk4Yy00NjEwLWI1MjQtYjc3NzJhN2RlNzk0  .
* [MemC3](https://github.com/efficient/memc3/) - An in-memory key-value cache based on concurrent cuckoo hashing.
* [Libart](https://github.com/armon/libart/) - Adaptive Radix Trees implemented in C .
* [Masstree](https://github.com/kohler/masstree-beta/) - Masstree, a fast, multi-core key-value store .
* [HyPer](http://hyper-db.de/) - A hybrid online transactional processing (OLTP) and online analytical processing (OLAP) high-performance main memory database system that is optimized for modern hardware .
* [HERD](https://github.com/efficient/HERD/) - A Highly Efficient key-value system for RDMA .
* [Nldb](https://github.com/Nanolat/nldb/) - Nanolat Database supporting 1M transactions per second .
* [Sophia](http://sphia.org/) - Modern embeddable key-value database designed for a high load environment .
* [FOEDUS](https://github.com/hkimura/foedus_code/) -  Transactional fast optimistic engine optimized for a large number of CPU cores and NVRAM storage (or fast SSD) .
* [FastBit_UDF](https://github.com/greenlion/FastBit_UDF/) -  MySQL UDF for creating, manipulating and querying FastBit indexes .
* [Jump Consistent Hash](https://github.com/anachronistic/jump-consistent-hash/) -  A Go implementation of the jump consistent hash .
* [Content Defined Chunking](https://moinakg.wordpress.com/2013/06/22/high-performance-content-defined-chunking/) -  High Performance Content Defined Chunking .
* [SSD optimizations](http://www.nodalink.com/blog_SSD_random_io_optimization_26_01_2014.html/) - Optimizing SSDs random IOPs, noop/tpps scheduler, rotational=0, add_random=0 .
* [Article-SSD](http://codecapsule.com/2014/02/12/coding-for-ssds-part-6-a-summary-what-every-programmer-should-know-about-solid-state-drives//) - Coding for SSDs - What every programmer should know about solid-state drives .
* [Article-Key-Value](http://codecapsule.com/2013/05/13/implementing-a-key-value-store-part-5-hash-table-implementations/) - Implementing a Key-Value Store .
* [Article-MVCC](http://highlyscalable.wordpress.com/2012/01/07/mvcc-transactions-key-value/) - Implementation of MVCC Transactions for Key-Value Stores .
* [Article-SSD](http://arstechnica.com/information-technology/2012/06/inside-the-ssd-revolution-how-solid-state-disks-really-work/) - Solid-state revolution: in-depth on how SSDs really work .
* [DB Redbook](http://www.redbook.io/) - Readings in Database Systems .



### Distributed Infrastructure for Cloud---Database and Storage
* [Cockroach](https://github.com/cockroachdb/cockroach/) - A Scalable, Geo-Replicated, Transactional Datastore .
* [TiDB](https://github.com/pingcap/tidb/) - Distributed NewSQL database compatible with MySQL protocol  .
* [ElastiCell](https://github.com/deepfabric/elasticell) - Cloud native key-value store with strong consistency and reliability .
* [Yugabyte](https://github.com/yugabyte/yugabyte-db) - Cloud native database store with strong consistency and reliability .
* [FBase](https://github.com/tiglabs/fbase) - Cloud native database store with strong consistency and reliability by JD.
* [Paxosstore](https://github.com/Tencent/paxosstore) - Cloud native key value store with strong consistency and reliability by WeChat.
* [Phxqueue](https://github.com/Tencent/phxqueue) - A high-availability, high-throughput and highly reliable distributed queue based on the Paxos algorithm.
* [Youzan-nsq](https://github.com/youzan/nsq) - Youzan's modification of nsq to provide cloud native capability from reliability to auto rebalancing.
* [Baidu-Elasticsearch](https://github.com/baidu/Elasticsearch) - Baidu's modification of elasticsearch to provide strong data consistency and full SQL.
* [ClickHouse](https://github.com/yandex/ClickHouse) - Yandex's distributed column store OLAP.
* [Palo](https://github.com/baidu/palo) - Baidu's distributed OLAP based on Google's Mesa paper.
* [MapD](https://github.com/mapd/mapd-core) - MapD OLAP based on GPU.
* [ContainerFS](https://github.com/tiglabs/containerfs) - Cloud native distributed filesystem for Kubernetes.
* [OpenEBS](https://github.com/openebs/openebs) - Cloud native filesystem for Kubernetes(non-distributed ).
* [Seaweed-FS](https://github.com/chrislusf/weed-fs/) - Distributed filesystem for small blob files.
* [Ambry](https://github.com/linkedin/ambry/) - Distributed filesystem for small and large blob files.
* [DistributedLog](https://github.com/twitter/distributedlog/) - High performance replicated log service.
* [Jepsen](http://jepsen.io/) - Techniques Jepsen occupies a particular niche of the correctness testing landscape .
* [Namazu](https://github.com/osrg/namazu/) - Programmable fuzzy scheduler for testing distributed system .
* [GPaxos](https://github.com/lichuang/gpaxos) - Golang Paxos implementation based on Phxpaxos .
* [Consensus-Yaraft](https://github.com/neverchanje/consensus-yaraft) - C++ Raft implementation based on Etcd's golang raft .
* [NOPaxos](https://github.com/UWSysLab/NOPaxos) - Network-Ordered Paxos .
* [TAPIR](https://github.com/UWSysLab/tapir) - Building Consistent Transactions with Inconsistent Replication .
* [Phat](https://github.com/rdadolf/phat/) - An implementation of the Chubby lock service protocol in Msgpack RPC .
* [Hydra](https://github.com/addthis/hydra/) - A distributed data processing and storage system originally developed at AddThis .
* [Summingbird](https://github.com/twitter/summingbird/) - Streaming MapReduce with Scalding and Storm https://twitter.com/summingbird .
* [Hustle](https://github.com/tspurway/hustle/) - A column oriented, embarrassingly distributed relational event database .
* [MDCC](https://github.com/hiranya911/mdcc/) - Multi-DataCenter Consistency protocol .
* [URingPaxos](https://github.com/sambenz/URingPaxos/) - High throughput atomic multicast protocol .
* [Course-CS6452](http://www.cs.cornell.edu/courses/cs6452/2012sp/lectures.php/) - Datacenter Networks and Services .

### Distributed Infrastructure for Cloud---Application
* [Pinpoint](https://github.com/naver/pinpoint/) - Non-intrusive Dapper-like APM solution .
* [CAT](https://github.com/dianping/cat/) - APM solution at Dianping Inc .
* [Brave](https://github.com/openzipkin/brave/) - Java version of OpenZipkin .
* [Appdash](https://github.com/sourcegraph/appdash/) - Golang version of Dapper .
* [Jaeger](https://github.com/jaegertracing/jaeger/) - Golang version of Dapper in Uber.
* [Cadence](https://github.com/uber/cadence/) - Microservice workflow orchestrator .
* [Zeebe](https://zeebe.io/) - Microservice workflow orchestrator .
* [F-Stack](https://github.com/F-Stack/f-stack/) -  Network framework with high performance based on DPDK .
* [DPVS](https://github.com/iqiyi/dpvs/) -  High performance Layer-4 load balancer based on DPDK .


### Distributed Infrastructure for Cloud---A(AI)B(BigData)C(Cloud)
* [Galaxy](https://github.com/baidu/galaxy/) - Naive scheduler for Baidu search cluster .
* [Cook](https://github.com/twosigma/Cook/) -  Fair job scheduler on Mesos for batch workloads and Spark .
* [Kube-arbitrator](https://github.com/kubernetes-incubator/kube-arbitrator/) - Cluster colocation scheduler for Kubernetes .
* [BigFlow](https://github.com/baidu/bigflow/) - Baidu dataflow operator .
* [Pulsar](https://github.com/pulsarIO) - Business level monitor and analysis .
* [Cubert](https://github.com/linkedin/Cubert/) - A fast and efficient batch computation engine for complex analysis and reporting of massive datasets on Hadoop .
* [Embulk](https://github.com/embulk/embulk/) - A plugin-based parallel bulk data loader that makes painful data integration works relaxed .
* [Gobblin](https://github.com/linkedin/gobblin/) - Data ingestion as a service .
* [Magpie](https://github.com/rootsongjc/magpie/) - Deploying and managing a Hadoop Yarn cluster with Docker Swarm .
* [Horovod](https://github.com/uber/horovod/) - Uber's modification of TensorFlow to provide RingReduce based on MPI.
* [Angel](https://github.com/Tencent/angel/) - Tencent's parameter server infrastructure to support machine learning.
* [Ytk-Learn](https://github.com/yuantiku/ytk-learn/) - Yuantiku's distributed machine learning platform.
* [Libble](https://github.com/LIBBLE/LIBBLE-PS/) - LIBBLE from NJU to provide faster convergence than SGD.
* [Gloo](https://github.com/facebookincubator/gloo/) - Facebook's communications library with various primitives for multi-machine training.
* [xLearn](https://github.com/aksnzhy/xlearn/) -  High Performance, Easy-to-use, and Scalable Machine Learning Package (C++, Python, R).
* [LASER](http://github.com/izenecloud/laser/) - A Scalable Response Prediction Platform For Online Advertising .
* [Hivemall](https://github.com/myui/hivemall/) - Scalable machine learning library for Hive/Hadoop .
* [Ml-ease](https://github.com/linkedin/ml-ease/) - ADMM based large scale logistic regression .
* [Jubatus](http://jubat.us/) - Distributed Online Machine Learning Framework .


### Concurrency
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
* [Lockfree Queue](https://github.com/krizhanovsky/NatSys-Lab/blob/master/lockfree_rb_q.cc/) -  Lock-free Condition Wait for Lock-free Multi-producer Multi-consumer Queue, see http://natsys-lab.blogspot.ru/2013/08/lock-free-condition-wait-for-lock-free.html .
* [Ssmem](https://github.com/LPD-EPFL/ssmem/) - A simple object-based memory allocator with epoch-based garbage collection, the publication "Asynchronized Concurrency: The Secret to Scaling Concurrent Search Data Structures" .
* [CLHT](https://github.com/LPD-EPFL/CLHT/) - A very fast and scalable (lock-based and lock-free) hash table that uses cache-line sized buckets .
* [Comsat](http://www.paralleluniverse.co/comsat/) - Comsat lets your application enjoy the scalability of asynchronous web-frameworks, serving many thousands of concurrent long-lived connections, or issuing hundreds of web-service calls for each request, all while maintaining the simple “thread per request” model .
* [Quasar-thrift](https://github.com/pinterest/quasar-thrift/) - Quasar fiber based Thrift RPC .
* [Seastar](http://www.seastar-project.org/) - Concurrency library in user space .
* [Article-TM](http://kukuruku.co/hub/cpp/transactional-memory-history-and-development/) - Transactional Memory: History and Development .


### System Performance And Profiling
* [Vmmlib](http://vmml.github.io/vmmlib/) - A templatized C++ vector and matrix math library .
* [Blaze-lib](https://code.google.com/p/blaze-lib/) - A high performance C++ math library .
* [Light-matrix](https://github.com/lindahua/light-matrix/) - A Light-weight and Fast Template Matrix Library .
* [Light-simd](https://github.com/lindahua/light-simd/) - A light weight library for SIMD based computation .
* [MathSimd](https://github.com/HeliumProject/MathSimd/) - SIMD-optimized math library in C++ .
* [Opti](https://github.com/herumi/opti/) - Experiment of x86/x64 optimization .
* [Fmath](https://github.com/herumi/fmath/) - Fast log and exp functions for x86/x64 SSE http://homepage1.nifty.com/herumi/soft/fmath.html .
* [Mie](https://github.com/herumi/mie/) - Fast string library with SSE4.2 .
* [Libsimdpp](https://github.com/p12tic/libsimdpp/) - Header-only zero-overhead C++ wrapper for SIMD intrinsics of multiple instruction sets .
* [Smart](https://github.com/yandex/smart/) - SMT-aware Real-time scheduler for Linux from Yandex.
* [Simple Binary Encoding](http://real-logic.github.io/simple-binary-encoding/) - Serialization with ultra low latency .
* [Farmhash](https://code.google.com/p/farmhash/) - FarmHash is a successor to CityHash, and includes many of the same tricks and techniques, several of them taken from Austin Appleby’s MurmurHash .
* [Proxygen](https://github.com/facebook/proxygen/) - A collection of C++ HTTP libraries including an easy to use HTTP server .
* [Yamail](https://github.com/yandex/yamail/) - YMail General Purpose Library .
* [WDT](https://github.com/facebook/wdt/) - Warp speed Data Transfer (WDT) is an embeddedable library (and command line tool) aiming to transfer data between 2 systems as fast as possible over multiple TCP paths .
* [UNetStack](https://github.com/bioothod/unetstack/) - Userspace TCP/IP stack .
* [CamIO](http://www.cl.cam.ac.uk/research/srg/netos/camsas/camio/) - Userspace IO abstraction .
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


### Search Engine and Information Retrieval
* [Vespa](https://github.com/vespa-engine/vespa) - Production ready search engine to support web-scale data .
* [SF1R](http://github.com/izenecloud/sf1r-lite) - A distributed massive data engine for enterprise/vertical search written in C++ .
* [BitFunnel](https://github.com/BitFunnel/BitFunnel) - Signature file based search engine from Bing .
* [Trinity](https://github.com/phaistos-networks/Trinity/) -  Trinity IR toolkit .
* [IResearch](https://github.com/iresearch-toolkit/iresearch/) -  IR toolkit to be used for ArangoDB .
* [Partitioned_elias_fano](https://github.com/ot/partitioned_elias_fano/) - Code used for the experiments in the paper "Partitioned Elias-Fano Indexes" .
* [Clustered_Partitioned_elias_fano](https://github.com/jermp/clustered_elias_fano_indexes/) - Code used for paper Clustered Elias-Fano Indexes" .
* [Data Structures for Inverted Indexes](https://github.com/ot/ds2i/) - Optimal Space-Time Tradeoffs for Inverted Indexes .
* [Surf](https://github.com/simongog/surf/) - SUccinct Retrieval Framework .
* [FastPFor](https://github.com/lemire/FastPFor/) - Fast integer compression .
* [Indexing](https://github.com/josephnoir/indexing/) - Experimenting with indexing on GPUs .
* [Genie](https://github.com/SeSaMe-NUS/genie/) -  Generic Inverted Index on GPU .
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
* [SIMD-Based-Posting-lists](https://github.com/maximecaron/SIMD-Based-Posting-lists/) - Implementation of Alexander A. Stepanov inverted Index Compression algorithms .
* [Groonga](http://groonga.org/) - Open-source fulltext search engine and column store .
* [Atire](http://atire.org/) - A search engine built using the most effective recent research techniques discovered by Information Retrieval researchers around the world .
* [Mg4j](http://mg4j.di.unimi.it/) - Academic search engine with succinct design(say quasi-succinct indices) .
* [Argos](https://github.com/windoze/Argos/) -  A structural data search engine .
* [MFRetrieval](https://github.com/Hui-Li/MFRetrieval/) -  Tools for maximum inner product retrieval in recommender systems .
* [Faiss](https://github.com/facebookresearch/faiss/) -  A library for efficient similarity search and clustering of dense vectors .
* [Lopq](https://github.com/yahoo/lopq/) -  Training of Locally Optimized Product Quantization (LOPQ) models for approximate nearest neighbor search of high dimensional data in Python and Spark .

# awesome-vector-ANN-search-papers
A list of papers in the field of approximate nearest neighbor search on high-dimensional vectors.

We organize papers according to **categories** and **research groups**. Other reading reference and notes for ANN study is coming soon.

Let's dive into ANN search and vector database!


## Introduction of ANN search
The introduction of ANN search is coming soon.

## Papers Organized with Categories

### Graph-based

This category collects papers that propose graph-based methods, without combining other three types of categories (e.g., tree-based, hash-based, quantization-based).

- Approximate nearest neighbor algorithm based on navigable small world graphs (IS2014),  Malkov et al. [[link]](https://www.researchgate.net/profile/Yu-Malkov/publication/259126397_Approximate_nearest_neighbor_algorithm_based_on_navigable_small_world_graphs/links/63733c302f4bca7fd06030b8/Approximate-nearest-neighbor-algorithm-based-on-navigable-small-world-graphs.pdf)
- ARKGraph: All-Range Approximate K-Nearest-Neighbor Graph (VLDB2023), Zuo et al. [[link]](https://www.vldb.org/pvldb/vol16/p2645-deng.pdf)
- EFANNA : An Extremely Fast Approximate Nearest Neighbor Search Algorithm Based on kNN Graph (2016), Fu et al. [[link]](https://arxiv.org/pdf/1609.07228)
- Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs (TPAMI2018), Malkov et al. [[link]](https://www.researchgate.net/profile/Yu-Malkov/publication/259126397_Approximate_nearest_neighbor_algorithm_based_on_navigable_small_world_graphs/links/63733c302f4bca7fd06030b8/Approximate-nearest-neighbor-algorithm-based-on-navigable-small-world-graphs.pdf)
- FANNG: Fast Approximate Nearest Neighbour Graphs (CVPR2016), Harwood et al. [[link]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Harwood_FANNG_Fast_Approximate_CVPR_2016_paper.pdf)
- Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph (VLDB2019), Fu et al. [[link]](https://www.vldb.org/pvldb/vol12/p461-fu.pdf)
- High Dimensional Similarity Search with Satellite System Graph: Efficiency, Scalability, and Unindexed Query Compatibility (TPAMI2021), Fu et al. [[link]](https://arxiv.org/pdf/1907.06146)
- Improving Approximate Nearest Neighbor Search through Learned Adaptive Early Termination (SIGMOD2020), Li et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3318464.3380600)
- Learning to Route in Similarity Graphs (ICML2019), Baranchuk et al. [[link]](http://proceedings.mlr.press/v97/baranchuk19a/baranchuk19a.pdf)
- Probabilistic Routing for Graph-Based Approximate Nearest Neighbor Search (2024), Lu et al. [[link]](https://arxiv.org/pdf/2402.11354)
- Reinforcement Routing on Proximity Graph for Efficient Recommendation (TOIS2023), Feng et al. [[link]](https://www.microsoft.com/en-us/research/uploads/prod/2022/03/paper.pdf)
- Steiner-Hardness: A Query Hardness Measure for Graph-Based ANN Indexes (VLDB2025), Wang et al. [[link]](https://arxiv.org/pdf/2408.13899)
- RoarGraph: A Projected Bipartite Graph for Efficient Cross-Modal Approximate Nearest Neighbor Search (VLDB2024), Chen et al. [[link]](https://www.vldb.org/pvldb/vol17/p2735-chen.pdf)


### Combining graph and other categories
- ELPIS: Graph-Based Similarity Search for Scalable Data Science (VLDB2023), Azizi et al. [[link]](https://www.vldb.org/pvldb/vol16/p1548-azizi.pdf)
- HVS: hierarchical graph structure based on voronoi diagrams for solving approximate nearest neighbor search (VLDB2021), Lu et al. [[link]](http://www.vldb.org/pvldb/vol15/p246-lu.pdf)
- Routing-Guided Learned Product Quantization for Graph-Based Approximate Nearest Neighbor Search (ICDE2024), Yue et al. [[link]](https://arxiv.org/pdf/2311.18724)
- Towards Efficient Index Construction and Approximate Nearest Neighbor Search in High-Dimensional Spaces (VLDB2023), Zhao et al. [[link]](https://www.vldb.org/pvldb/vol16/p1979-zhao.pdf)



### Partitions-based
- Learning Space Partitions for Nearest Neighbor Search (ICLR2020),  et al. [[link]](https://arxiv.org/pdf/1901.08544)
- BLISS: A Billion scale Index using Iterative Re-partitioning (SIGKDD2022), Gupta et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539414)
- Learning Balanced Tree Indexes for Large-Scale Vector Retrieval (SIGKDD2023), Li et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3580305.3599406)
- Learned Probing Cardinality Estimation for High-Dimensional Approximate NN Search (ICDE2023), Zheng et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10184837)
- Learning-based query optimization for multi-probe approximate nearest neighbor search (VLDBJ2023), Zhang et al. [[link]](https://link.springer.com/article/10.1007/s00778-022-00762-0)



### Quantization-based

- Practical and Asymptotically Optimal Quantization of High-Dimensional Vectors in Euclidean Space for Approximate Nearest Neighbor Search (2024), Gao et al. [[link]](https://arxiv.org/pdf/2409.09913)
- RaBitQ: Quantizing High-Dimensional Vectors with a Theoretical Error Bound for Approximate Nearest Neighbor Search (SIGMOD2024), Gao et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3654970)
- Similarity Search in the Blink of an Eye with Compressed Indices (VLDB2023), Aguerrebere et al. [[link]](https://arxiv.org/pdf/2304.04759)
- Model-enhanced Vector Index (NeurIPS2023), Zhang et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2023/file/ac112e8ffc4e5b9ece32070440a8ca43-Paper-Conference.pdf)
- Knowledge Distillation for High Dimensional Search Index (NeurIPS2024), Lu et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2023/file/6a15378acabd1aef017ec79a3ed744d2-Paper-Conference.pdf)
- Accelerating Large-Scale Inference with Anisotropic Vector Quantization, ScaNN, (ICML2020), Guo et al. [[link]](https://dl.acm.org/doi/abs/10.5555/3524938.3525302)



### Hash-based
- DB-LSH: Locality-Sensitive Hashing with Query-based Dynamic Bucketing (ICDE2023), Tian et al. [[link]](https://ieeexplore.ieee.org/abstract/document/9835575)
- DB-LSH 2.0: Locality-Sensitive Hashing With Query-Based Dynamic Bucketing (TKDE2023), Tian et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10184454)
- MP-RW-LSH: an efficient multi-probe LSH solution to ANNS-<i>L</i><sub>1</sub> (VLDB2021), Wang et al. [[link]](https://vldb.org/pvldb/vol14/p3267-wang.pdf)
- PM-LSH: a fast and accurate in-memory framework for high-dimensional approximate NN and closest pair search (VLDB2022), Zheng et al. [[link]](https://arxiv.org/pdf/2107.05537)
- Query-aware locality-sensitive hashing for approximate nearest neighbor search (VLDB2015), Huang et al. [[link]](https://www.researchgate.net/profile/Jianlin-Feng/publication/292671953_Query-aware_locality-sensitive_hashing_for_approximate_nearest_neighbor_search/links/59a41df1a6fdcc773a371efc/Query-aware-locality-sensitive-hashing-for-approximate-nearest-neighbor-search.pdf)
- LIDER: an efficient high-dimensional learned index for large-scale dense passage retrieval (VLDB2022), Wang et al. [[link]](https://www.vldb.org/pvldb/vol16/p154-wang.pdf)
- DET-LSH: A Locality-Sensitive Hashing Scheme with Dynamic Encoding Tree for Approximate Nearest Neighbor Search (VLDB2024), Wei et al. [[link]](https://arxiv.org/pdf/2406.10938)


### Tree-based
- DIDS: Double Indices and Double Summarizations for Fast Similarity Search (VLDB2024), Hu et al. [[link]](https://www.vldb.org/pvldb/vol17/p2198-wang.pdf)
- Adaptive Indexing in High-Dimensional Metric Spaces (VLDB2023), Lampropoulos et al. [[link]](https://cs.au.dk/~karras/p2525-mamoulis.pdf)
- Hercules Against Data Series Similarity Search (VLDB2022), Echihabi et al. [[link]](https://www.vldb.org/pvldb/vol15/p2005-echihabi.pdf)
- Scalable Nearest Neighbor Algorithms for High Dimensional Data (TPAMI20), Muja et al. [[link]](https://ieeexplore.ieee.org/iel7/34/4359286/06809191.pdf)
- <i>i</i> SAX: indexing and mining terabyte sized time series (SIGKDD2008), Shieh et al. [[link]](http://alumni.cs.ucr.edu/~shiehj/files/iSAX.pdf)

### Disk available

- DiskANN: Fast Accurate Billion-point Nearest Neighbor Search on a Single Node (NeurIPS2019), Subramanya et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2019/file/09853c7fb1d3f8ee67a61b6bf4a7f8e6-Paper.pdf)
- DiskANN++: Efficient Page-based Search over Isomorphic Mapped Graph Index using Query-sensitivity Entry Vertex (2023), Ni et al. [[link]](https://arxiv.org/pdf/2310.00402)
- Filtered − DiskANN: Graph Algorithms for Approximate Nearest Neighbor Search with Filters (Web2023), Gollapudi et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3543507.3583552)
- FreshDiskANN: A Fast and Accurate Graph-Based ANN Index for Streaming Similarity Search (2021), Singh et al. [[link]](https://dcreager.net/pdf/Singh2021.pdf)
- SPANN: Highly-efﬁcient Billion-scale Approximate Nearest Neighbor Search (NeurIPS2021), Chen et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2021/file/299dc35e747eb77177d9cea10a802da2-Paper.pdf)
- SPFresh: Incremental In-Place Update for Billion-Scale Vector Search (SOSP2023), Xu et al. [[link]](https://dl.acm.org/doi/abs/10.1145/3600006.3613166)



### Survey and benchmark

- A Comprehensive Survey and Experimental Comparison of Graph-Based Approximate Nearest Neighbor Search (VLDB2021), Wang et al. [[link]](https://www.vldb.org/pvldb/vol14/p1964-wang.pdf)
- ParlayANN: Scalable and Deterministic Parallel GraphBased Approximate Nearest Neighbor Search Algorithms (PPoPP2024), Manohar et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3627535.3638475)
- Deep Learning for Approximate Nearest Neighbour Search: A Survey and Future Directions (TKDE2022), Li et al. [[link]](https://ieeexplore.ieee.org/abstract/document/9942356)
- Survey of Vector Database Management Systems (VLDB2024), Pan et al. [[link]](https://arxiv.org/pdf/2310.14021)



### Hybrid query

- SeRF: Segment Graph for Range-Filtering Approximate Nearest Neighbor Search (SIGMOD2024), Zuo et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3639324)
- Filtered − DiskANN: Graph Algorithms for Approximate Nearest Neighbor Search with Filters (Web2023), Gollapudi et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3543507.3583552)
- High-Throughput Vector Similarity Search in Knowledge Graphs (SIGMOD2023), Mohoney et al. [[link]](https://arxiv.org/pdf/2304.01926)
- Navigable Proximity Graph-Driven Native Hybrid Queries with Structured and Unstructured Constraints (2022), Wang et al. [[link]](https://arxiv.org/pdf/2203.13601)
- AnalyticDB-V: a hybrid analytical engine towards query fusion for structured and unstructured data (VLDB2020), Wei et al. [[link]](https://vldb.org/pvldb/vol13/p3152-wei.pdf)


### Computation acceleration
- High-Dimensional Approximate Nearest Neighbor Search: with Reliable and Efficient Distance Comparison Operations (SIGMOD2023), Gao et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3589282)
- Juno: Optimizing High-Dimensional Approximate Nearest Neighbour Search with Sparsity-Aware Algorithm and Ray-Tracing Core Mapping (ASPLOS2024), Liu et al. [[link]](https://horizon-lab.org/pubs/asplos24-juno.pdf)
- FINGER: Fast Inference for Graph-based Approximate Nearest Neighbor Search (Web2023), Chen et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3543507.3583318)

### Vector database system

- Milvus: A Purpose-Built Vector Data Management System (SIGMOD2021), Wang et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3448016.3457550)
- Manu: A Cloud Native Vector Database Management System (VLDB2022), Guo et al. [[link]](https://www.vldb.org/pvldb/vol15/p3548-yan.pdf)
- Vexless: A Serverless Vector Data Management System Using Cloud Functions (VLDB2024), Su et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3654990)
- Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment (SIGMOD2024), Wang et al. [[link]](https://arxiv.org/pdf/2401.02116)
- Efficient Approximate Nearest Neighbor Search in Multi-dimensional Databases (SIGMOD2023), Peng et al. [[link]](https://www.comp.hkbu.edu.hk/~edisonchan/publication/tau-MNG.pdf)
- VBASE: Unifying Online Vector Similarity Search and Relational Queries via Relaxed Monotonicity (OSDI2023), Zhang et al. [[link]](https://www.usenix.org/system/files/osdi23-zhang-qianxi_1.pdf)
- LANNS: a web-scale approximate nearest neighbor lookup system (VLDB2021), Doshi et al. [[link]](https://arxiv.org/pdf/2010.09426)
- SingleStore-V: An Integrated Vector Database System in
SingleStore (VLDB2024), Chen et al. [[link]](https://cs.purdue.edu/homes/csjgwang/pubs/VLDB24_SingleStoreVec.pdf)

### Threoratical

- Graph-based Nearest Neighbor Search:  From Practice to Theory (ICML2020), Prokhorenkova et al. [[link]](http://proceedings.mlr.press/v119/prokhorenkova20a/prokhorenkova20a.pdf)



### Multi-metric spaces

- HJG: An Effective Hierarchical Joint Graph for ANNS in Multi-Metric Spaces (ICDE2024), Zhu et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10597848)



### Reverse kANN

- Efficient Reverse k Approximate Nearest Neighbor Search Over High-Dimensional Vectors (ICDE2024), Song et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10598048)




## Papers Organized with Research Groups
- Yury Malkov, OpenAI
    1. Approximate nearest neighbor algorithm based on navigable small world graphs (IS2014),  Malkov et al. [[link]](https://www.researchgate.net/profile/Yu-Malkov/publication/259126397_Approximate_nearest_neighbor_algorithm_based_on_navigable_small_world_graphs/links/63733c302f4bca7fd06030b8/Approximate-nearest-neighbor-algorithm-based-on-navigable-small-world-graphs.pdf)
    2. Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs (TPAMI2018), Malkov et al. [[link]](https://www.researchgate.net/profile/Yu-Malkov/publication/259126397_Approximate_nearest_neighbor_algorithm_based_on_navigable_small_world_graphs/links/63733c302f4bca7fd06030b8/Approximate-nearest-neighbor-algorithm-based-on-navigable-small-world-graphs.pdf)

- Zilliz
    1. Milvus: A Purpose-Built Vector Data Management System (SIGMOD2021), Wang et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3448016.3457550)
    2.  Manu: A Cloud Native Vector Database Management System (VLDB2022), Guo et al. [[link]](https://www.vldb.org/pvldb/vol15/p3548-yan.pdf)
    3. Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment (SIGMOD2024), Wang et al. [[link]](https://arxiv.org/pdf/2401.02116)

- Qi Chen, Microsoft Research
    1. SPANN: Highly-efﬁcient Billion-scale Approximate Nearest Neighbor Search (NeurIPS2021), Chen et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2021/file/299dc35e747eb77177d9cea10a802da2-Paper.pdf)
    2. SPFresh: Incremental In-Place Update for Billion-Scale Vector Search (SOSP2023), Xu et al. [[link]](https://dl.acm.org/doi/abs/10.1145/3600006.3613166)
    3. VBASE: Unifying Online Vector Similarity Search and Relational Queries via Relaxed Monotonicity (OSDI2023), Zhang et al. [[link]](https://www.usenix.org/system/files/osdi23-zhang-qianxi_1.pdf)

- Dong Deng, Rutgers University
    1. SeRF: Segment Graph for Range-Filtering Approximate Nearest Neighbor Search (SIGMOD2024), Zuo et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3639324)
    2. ARKGraph: All-Range Approximate K-Nearest-Neighbor Graph (VLDB2023), Zuo et al. [[link]](https://www.vldb.org/pvldb/vol16/p2645-deng.pdf)

- Cong Fu, Zhejiang University
    1. EFANNA : An Extremely Fast Approximate Nearest Neighbor Search Algorithm Based on kNN Graph (2016), Fu et al. [[link]](https://arxiv.org/pdf/1609.07228)
    2. Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph (VLDB2019), Fu et al. [[link]](https://www.vldb.org/pvldb/vol12/p461-fu.pdf)

- Kejing Lu, Nagoya University
    1. Probabilistic Routing for Graph-Based Approximate Nearest Neighbor Search (2024), Lu et al. [[link]](https://arxiv.org/pdf/2402.11354)
    2. HVS: hierarchical graph structure based on voronoi diagrams for solving approximate nearest neighbor search (VLDB2021), Lu et al. [[link]](http://www.vldb.org/pvldb/vol15/p246-lu.pdf)

- Defu Lian, University of Science and Technology of China
    1. Knowledge Distillation for High Dimensional Search Index (NeurIPS2024), Lu et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2023/file/6a15378acabd1aef017ec79a3ed744d2-Paper-Conference.pdf)
    2. Reinforcement Routing on Proximity Graph for Efficient Recommendation (TOIS2023), Feng et al. [[link]](https://www.microsoft.com/en-us/research/uploads/prod/2022/03/paper.pdf)
    3. Learning Balanced Tree Indexes for Large-Scale Vector Retrieval (SIGKDD2023), Li et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3580305.3599406)

- Themis Palpanas, LIPADE, Université Paris Cité
    1. Steiner-Hardness: A Query Hardness Measure for Graph-Based ANN Indexes (VLDB2025), Wang et al. [[link]](https://arxiv.org/pdf/2408.13899)
    2. ELPIS: Graph-Based Similarity Search for Scalable Data Science (VLDB2023), Azizi et al. [[link]](https://www.vldb.org/pvldb/vol16/p1548-azizi.pdf)
    3. Hercules Against Data Series Similarity Search (VLDB2022), Echihabi et al. [[link]](https://www.vldb.org/pvldb/vol15/p2005-echihabi.pdf)
    4. DET-LSH: A Locality-Sensitive Hashing Scheme with Dynamic Encoding Tree for Approximate Nearest Neighbor Search (VLDB2024), Wei et al. [[link]](https://arxiv.org/pdf/2406.10938)

- Guoliang Li, Tsinghua University
    1. Survey of Vector Database Management Systems (VLDB2024), Pan et al. [[link]](https://arxiv.org/pdf/2310.14021)

- Bin Cui, Peking University
    1. Model-enhanced Vector Index (NeurIPS2023), Zhang et al. [[link]](https://proceedings.neurips.cc/paper_files/paper/2023/file/ac112e8ffc4e5b9ece32070440a8ca43-Paper-Conference.pdf)

- Xi Zhao, Xiaofang Zhou, Hong Kong University of Science and Technology
    1. Towards Efficient Index Construction and Approximate Nearest Neighbor Search in High-Dimensional Spaces (VLDB2023), Zhao et al. [[link]](https://www.vldb.org/pvldb/vol16/p1979-zhao.pdf)
    2. DB-LSH: Locality-Sensitive Hashing with Query-based Dynamic Bucketing (ICDE2023), Tian et al. [[link]](https://ieeexplore.ieee.org/abstract/document/9835575)
    3. DB-LSH 2.0: Locality-Sensitive Hashing With Query-Based Dynamic Bucketing (TKDE2023), Tian et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10184454)
    
- Xiaoliang Xu, Yuxiang Wang, Hangzhou Dianzi University
    1. Routing-Guided Learned Product Quantization for Graph-Based Approximate Nearest Neighbor Search (ICDE2024), Yue et al. [[link]](https://arxiv.org/pdf/2311.18724)
    2. DiskANN++: Efficient Page-based Search over Isomorphic Mapped Graph Index using Query-sensitivity Entry Vertex (2023), Ni et al. [[link]](https://arxiv.org/pdf/2310.00402)
    3. Navigable Proximity Graph-Driven Native Hybrid Queries with Structured and Unstructured Constraints (2022), Wang et al. [[link]](https://arxiv.org/pdf/2203.13601)
    4. Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment (SIGMOD2024), Wang et al. [[link]](https://arxiv.org/pdf/2401.02116)
    
- Jianyang Gao, Cheng Long, Nanyang Technological University
    1. RaBitQ: Quantizing High-Dimensional Vectors with a Theoretical Error Bound for Approximate Nearest Neighbor Search (SIGMOD2024), Gao et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3654970)
    2. High-Dimensional Approximate Nearest Neighbor Search: with Reliable and Efficient Distance Comparison Operations (SIGMOD2023), Gao et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3589282)

- Wei Wang, Fudan University
    1. Steiner-Hardness: A Query Hardness Measure for Graph-Based ANN Indexes (VLDB2025), Wang et al. [[link]](https://arxiv.org/pdf/2408.13899)

- Wei Wang, Hong Kong University of Science and Technology (Guangzhou)
    1. Deep Learning for Approximate Nearest Neighbour Search: A Survey and Future Directions (TKDE2022), Li et al. [[link]](https://ieeexplore.ieee.org/abstract/document/9942356)

- Pengcheng Zhang, Bin Yao, Shanghai Jiao Tong University
    1. Learning-based query optimization for multi-probe approximate nearest neighbor search (VLDBJ2023), Zhang et al. [[link]](https://link.springer.com/article/10.1007/s00778-022-00762-0)

- Bolong Zheng, Huazhong University of Science and Technology
    1. Learned Probing Cardinality Estimation for High-Dimensional Approximate NN Search (ICDE2023), Zheng et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10184837)
    2. PM-LSH: a fast and accurate in-memory framework for high-dimensional approximate NN and closest pair search (VLDB2022), Zheng et al. [[link]](https://arxiv.org/pdf/2107.05537)

- Jianguo Wang, Purdue University
    1. Vexless: A Serverless Vector Data Management System Using Cloud Functions (VLDB2024), Su et al. [[link]](https://dl.acm.org/doi/pdf/10.1145/3654990)
- Lu Chen, Zhejiang University
    1. HJG: An Effective Hierarchical Joint Graph for ANNS in Multi-Metric Spaces (ICDE2024), Zhu et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10597848)
- Bin Yao, Shanghai Jiao Tong University
    1. Efficient Reverse k Approximate Nearest Neighbor Search Over High-Dimensional Vectors (ICDE2024), Song et al. [[link]](https://ieeexplore.ieee.org/abstract/document/10598048)





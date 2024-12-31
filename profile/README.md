## 1. Knowledge Graph
A knowledge graph (KG) consists of numerous triples, in which each triple, i.e., (head entity, relation, tail entity), denotes an assertion. By embedding KGs into low-dimensional representations, we could integrate them into deep learning models to perform various tasks, such as search and recommendation.<br>

**1.1 Question Answering over Knowledge Graphs**<br>
[HamQA_TheWebConf23](https://github.com/DEEP-PolyU/HamQA_TheWebConf23)<br>
[KEQA_WSDM19](https://github.com/DEEP-PolyU/KEQA_WSDM19)<br>

**1.2 Knowledge Graph Refinement**<br>
Real-world KGs often contain many false assertions, which were inevitably injected during the construction of KGs. We propose to investigate error-aware KG learning to eliminate the impact of errors on KG-based systems.<br>
[KAEL_WSDM23](https://github.com/DEEP-PolyU/KAEL_WSDM23)<br>
[CAGED_CIKM22](https://github.com/DEEP-PolyU/CAGED_CIKM22)<br>
[LLM4EA NeurIPS24](https://github.com/chensyCN/llm4ea_official)

## 2. Attributed Network Learning
Networks are widely adopted to represent the relations between objects in many disciplines. In real-world scenarios, nodes are often associated with a rich set of data describing their characteristics. We model these systems as attributed networks. Our goal is to develop effective, scalable, and human-centric learning algorithms for attributed networks, to enable their actionable patterns to be easily accessible and interpretable to data consumers.<br>

**2.1 Datasets**<br>
[BlogCatalog](https://www4.comp.polyu.edu.hk/~xiaohuang/docs/BlogCatalog.mat.zip) is an undirected network with 5,196 nodes and 171,743 edges, associated with node attributes of dimension 8,189.<br>
[Flickr](https://www4.comp.polyu.edu.hk/~xiaohuang/docs/Flickr.mat.zip) is an undirected network with 7,575 nodes and 239,738 edges, associated with node attributes of dimension 12,047.<br>
[Yelp_multilabel](https://www4.comp.polyu.edu.hk/~xiaohuang/docs/Yelp_multilabel.mat.zip) is an undirected network with 249,012 nodes and 1,779,803 edges, associated with node attributes of dimension 20,000.<br>

**2.2 Attributed network embedding**<br>
[FeatWalk_AAAI19](https://github.com/DEEP-PolyU/FeatWalk_AAAI19)<br>
[GraphRNA_KDD19](https://github.com/DEEP-PolyU/GraphRNA_KDD19)<br>
[AANE_SDM17](https://github.com/DEEP-PolyU/AANE_Python)<br>

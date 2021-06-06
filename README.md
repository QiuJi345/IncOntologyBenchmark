Copyright 2021 by Nanjing University of Posts and
Telecommunication. 

Time: 24/5/2021  Authors:  Qiu Ji & Weizhuo Li Shiqi Zhou & Guilin Qi & Yuanfang Li

Mail: qiuji@njupt.edu.cn & lwz@njupt.edu.cn & b17070710@njupt.edu.cn & gqi@seu.edu.cn & yuanfang.li@monash.edu

Description: A Benchmark for Incoherent Ontologies


# 1. Introduction:
We construct a comprehensive  benchmark for incoherent ontologies. It contains 116 incoherent ontologies in total which consists of 58 existing ontologies and 58 new incoherent ontologies constructed by four construction methods. With this benchmark, we evaluate five representative ontology debugging tools (namely, CPDebug, ProtegeBl, PelletBl, RadonRelAll, SwoopBl) w.r.t. MUPS number and time. We also evaluate these incoherent ontologies based on 11 classic metrics, such as incoherence ratio and size of a cardinality-minimal removal. These metrics could reflect ontology incoherence from various dimensions. The conclusion could guide researchers to select different incoherent ontologies and corresponding ontology debugging tools.  Besides, the availability of our benchmark could make a contribution to the community of ontology debugging and repair fields.



# 2. Usage:
This benchmark contains 116 incoherent ontologies in total ( see folder of "data"): 
- 1.1-existingOnts: 18 existing incoherent ontologies
- 1.2-MergeOntologies: 20 merged incoherent ontologies
- 1.3-subOnts: 20 incoherent sub-ontologies
- 2.1-InjectUCsFromScratch: 20 new incoherent ontologies constructed by construciton method NS
- 2.2-InjectUCsWithOnto: 20 new incoherent ontologies constructed by construciton method EC
- 2.3-mipsRel: 20 new incoherent ontologies constructed by construciton method OM
- 3-InjectIncoHybrid:  22 new incoherent ontologies constructed by our hybrid algorithm


# 3. Methods of constructing incoherent ontologies:
In our paper, six construction methods have been implemented and their usage can be found below.
- Construct incoherent ontologies through ontology matching:
- Construct incoherent ontologies by extracting sub-ontologies
- Construct incoherent ontologies by construction method NS:
- Construct incoherent ontologies by construction method EC:
- Construct incoherent ontologies by construction method OM:
- Construct incoherent ontologies by construction method HA:


# 4. Ontology debugging tools used:
We evaluated five representative ontology debugging tools. Their implementations and the source code to invoke an ontology debugging tool can be downloaded:
- [CPDebug]( http://www.zhyweb.cn/cpdebrep/index.php): A clash path-based ontology debugging method ([source code]())
- ProtegeBl: It is provided by the famous ontology editor [Protege](https://protege.stanford.edu/) ([source code]())
- PelletBl: It is the debugging functionality implemented in OWL DL ontology reasoner [Pellet]( https://github.com/ignazio1977/pellet) ([source code]())
- RadonRelAll: It represents the relevance-directed debugging algorithm  implemented in RaDON ([source code]())
- SwoopBl: It is the debugging functionality provided by ontology editing browser [SWOOP]( https://github.com/ronwalf/swoop) ([source code]())


# 5. Evaluation results:


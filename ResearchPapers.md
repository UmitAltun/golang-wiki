This page lists academic and industry research papers about Go or using Go as the implementation language.
## 2021

- Gobra: Modular Specification and Verification of Go Programs (F. A. Wolf, L. Arquint, M. Clochard, W. Oortwijn, J. C. Pereira, P. Müller)
  - [CAV'21](https://doi.org/10.1007/978-3-030-81685-8_17)
  - [web-page](https://gobra.ethz.ch)

## 2020

- Uncovering the Hidden Dangers: Finding Unsafe Go Code in the Wild (J. Lauinger, L. Baumgärtner, A. Wickert, M. Mezini) 
  - [arxiv](https://arxiv.org/abs/2010.11242)
  - [go-geiger](https://github.com/jlauinger/go-geiger)
  - [go-safer](https://github.com/jlauinger/go-safer)
  - [Study results](https://github.com/stg-tud/unsafe_go_study_results)
  - [Go unsafe.Pointer vulnerability POCs](https://github.com/jlauinger/go-unsafepointer-poc)
  - [Conference talk](https://www.youtube.com/watch?v=adn6A7nG61I)
- Lightweight Preemptible Functions (S. Boucher, A. Kalia, D. Andersen, M. Kaminsky)
  - [Usenix'20](https://www.usenix.org/conference/atc20/presentation/boucher)
- From Folklore to Fact: Comparing Implementations of Stacks and Continuations (K. Farvadin, J. Reppy)
  - [PLDI'20](https://dl.acm.org/doi/abs/10.1145/3385412.3385994)
- Featherweight Go (R. Griesemer, R. Hu, W. Kokke, J. Lange, I. Taylor, B. Toninho, P. Wadler, N. Yoshida)
  - [arxiv](https://arxiv.org/abs/2005.11710)
- GoPi: Compiling linear and static channels in Go (M. Giunti)
  - [pdf](http://ctp.di.fct.unl.pt/~mgiunti/preprints/coord20_camera.pdf)
  - [github](https://github.com/marcogiunti/gopi) 
- Fencing off Go: Liveness and Safety for Channel-Based Programming
  - [pdf](http://mrg.doc.ic.ac.uk/publications/fencing-off-go-liveness-and-safety-for-channel-based-programming/long.pdf)
- Breaking Type-Safety in Go: An Empirical Study on the Usage of the unsafe Package (D. Costa, S. Mujahid, R. Abdalkareem, E. Shihab)
  - [arxiv](https://arxiv.org/abs/2006.09973)
- Static Race Detection and Mutex Safety and Liveness for Go Programs (J. Gabet, N. Yoshida)
  - [arxiv](https://arxiv.org/abs/2004.12859)
  - [github](https://github.com/JujuYuki/godel2)
- EdgeKV: Decentralized, scalable, and consistent storage for the edge (K. Sonbol, Ö. Özkasap, I. Al-Oqily, M. Aloqaily)
  - [arxiv](https://arxiv.org/abs/2006.15594)
- Bypassing memory safety mechanisms through speculative control flow hijacks (A. Mambretti, A. Sandulescu, A. Sorniotti, W. Robertson, E. Kirda, A. Kurmus)
  - [arxiv](https://arxiv.org/abs/2003.05503)
  - [CL](https://go-review.googlesource.com/c/go/+/222660)
- Bounded verification of message-passing concurrency in Go using Promela and Spin (N. Dilley, J. Lange)
  - [arxiv](https://arxiv.org/abs/2004.01323v1)
  - [github](https://github.com/nicolasdilley/Gomela)

## 2019

- Software Microbenchmarking in the Cloud. How Bad is it Really?. Laaber, Scheuner, and Leitner. In: Empirical Software Engineering.
  - [preprint](http://t.uzh.ch/T4)
  - [DOI](http://dx.doi.org/10.1007/s10664-019-09681-1)
  - [replication package](https://doi.org/10.6084/m9.figshare.7546703)

- Understanding Real-World Concurrency Bugs in Go (Tu, Liu, Song, Zhang)
  - [ASPLOS'19 preprint](https://songlh.github.io/paper/go-study.pdf)
  - [web](https://github.com/system-pclub/go-concurrency-bugs)

- An empirical study of messaging passing concurrency in Go projects (N. Dilley, J. Lange)
  - [SANER'19 pre-print](https://www.cs.kent.ac.uk/people/staff/jl703/papers/dilley-lange-saner19-preprint.pdf)
  - [web-page](https://www.cs.kent.ac.uk/people/staff/jl703/go-survey/)

- A comparison of three programming languages for a full-fledged next-generation sequencing tool (Costanza, Herzeel, Verachtert)
  - [biorvix](https://www.biorxiv.org/content/10.1101/558056v1?rss=1)

- Exploring polyglot software frameworks in ALICE with FairMQ and fer
  - [arxiv](https://arxiv.org/abs/1901.04834)
  - https://github.com/sbinet-alice/fer

- Flash: Efficient Dynamic Routing for Offchain Networks
  - [arxiv](https://arxiv.org/abs/1902.05260)

- RepChain: A Reputation based Secure, Fast and High Incentive Blockchain System via Sharding
  - [arxiv](https://arxiv.org/abs/1901.05741)

- Drynx: Decentralized, Secure, Verifiable System for Statistical Queries and Machine Learning on Distributed Datasets
  - [arxiv](https://arxiv.org/abs/1902.03785)

- STYLE-ANALYZER: fixing code style inconsistencies with interpretable unsupervised algorithms
  - [arxiv](https://arxiv.org/pdf/1904.00935.pdf)

- Linear-Time Inference for Pairwise Comparisons with Gaussian-Process Dynamics
  - [arxiv](https://arxiv.org/abs/1903.07746)
## 2018

- An Evaluation of Open-Source Software Microbenchmark Suites for Continuous Performance Assessment. Laaber and Leitner. In: MSR ’18: 15th International Conference on Mining Software Repositories.
  - [preprint](https://www.zora.uzh.ch/id/eprint/159079/1/msr18-author-version.pdf)
  - [DOI](https://doi.org/10.1145/3196398.3196407)
  - [replication package](https://doi.org/10.6084/m9.figshare.5982253)

- An Analysis of Quorum-based Abstractions: A Case Study using Gorums to Implement Raft. Sebastian Pedersen, Hein Meling, and Leander Jehl. In: Proceedings of the 2018 Workshop on Advanced Tools, Programming Languages, and PLatforms for Implementing and Evaluating Algorithms for Distributed systems, ApPLIED@PODC 2018, Egham, United Kingdom, July 27, 2018. ACM, 2018.
  - [doi:10.1145/3231104.3231957](https://doi.org/10.1145/3231104.3231957)
  - [Raft implementation in Gorums](https://github.com/relab/raft)

- Implementation and evaluation of secure and scalable anomaly-based network intrusion detection (P. Mieden)
  - [pdf](https://www.researchgate.net/publication/329815346_Implementation_and_evaluation_of_secure_and_scalable_anomaly-based_network_intrusion_detection?_iepl%5BviewId%5D=l30CNV1Mc1vme3xnwNE1OT0J&_iepl%5Bcontexts%5D%5B0%5D=projectUpdatesLog&_iepl%5BtargetEntityId%5D=PB%3A329815346&_iepl%5BinteractionType%5D=publicationTitle)
  - [code](https://github.com/dreadl0ck/netcap)
  - [presentation](https://www.researchgate.net/publication/329815099_Bachelor_thesis_Presentation_Implementation_and_evaluation_of_secure_and_scalable_anomaly-based_network_intrusion_detection)

- ProIO: An Event-Based I/O Stream Format for Protobuf Messages (D. Blyth, J. Alcaraz, S. Binet, S.V. Chekanov)
  - [arXiv:1812.03967](https://arxiv.org/abs/1812.03967)
  - [proio-org/go-proio](https://godoc.org/github.com/proio-org/go-proio)

- The latest gossip on BFT consensus (Buchman, Kwon, Milosevic)
  - [pdf](https://arxiv.org/abs/1807.04938)

- Distributed Programming using Role-Parametric Session Types in Go (Castro, Hu, Jongmans, NG, Yoshida)
  - [pdf](https://www.doc.ic.ac.uk/research/technicalreports/2018/DTRS18-4.pdf)

- Observing the Evolution of QUIC Implementations, (Piraux, De Coninck, Bonaventure)
  - [pdf](https://arxiv.org/abs/1810.09134)

- Cody Cutler, M. Frans Kaashoek, and Robert T. Morris, "The benefits and costs of writing a POSIX kernel in a high-level language"
  - [presentation](https://www.usenix.org/conference/osdi18/presentation/cutler)
  - [code](https://github.com/mit-pdos/biscuit)

- Voit, Sebastian Peter Johann. "Writing Network Drivers in Go."
  - [pdf](https://www.net.in.tum.de/fileadmin/bibtex/publications/theses/2018-ixy-go.pdf)

- "MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation" (Shankara Pailoor, Andrew Aday, Suman Jana) USENIX Security 2018
  - [pdf](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-pailoor.pdf)

- "Process-Local Static Analysis of Synchronous Processes" (Jan Midtgaard, Flemming Nielson, Hanne Riis Nielson) SAS 2018
  - [full version PDF](http://janmidtgaard.dk/papers/Midtgaard-Nielson-Nielson%3aSAS18-full.pdf)
  - [prototype](https://github.com/jmid/nano-go)

- "Inferring and Asserting Distributed System Invariants" (Stewart Grant, Hendrik Cech, Ivan Beschastnikh) ICSE 2018 Technical Papers
  - [pdf](https://www.cs.ubc.ca/~bestchai/papers/dinv-icse18.pdf)
  - [bitbucket.org/bestchai/dinv/](https://bitbucket.org/bestchai/dinv/) _"DInv is a distributed system data invariant detector"_  ; _"DInv is written in go lang"_ 

- "Revisiting the Vector Space Model: Sparse Weighted Nearest-Neighbor Method for Extreme Multi-Label Classification." (Tatsuhiro Aoshima, Kei Kobayashi, Mihoko Minami)  [arXiv:1802.03938](https://arxiv.org/abs/1802.03938) stat.ML,
  - [PDF:arXiv:1802.03938-stat.ML](https://arxiv.org/pdf/1802.03938.pdf)
  - [github.com/hiro4bbh/sticker ](https://github.com/hiro4bbh/sticker)  _"...We have published
our implementation sticker (Aoshima, 2018) written in Golang (Golang, 2009)..."_
  - keywords: sticker, machine-learning, classification

- A Static Verification Framework for Message Passing in Go using Behavioural Types (J. Lange, N. Ng, B. Toninho, N. Yoshida)
  - [accepted draft](http://mrg.doc.ic.ac.uk/publications/a-static-verification-framework-for-message-passing-in-go-using-behavioural-types/draft.pdf) at [ICSE 2018](https://www.icse2018.org/track/icse-2018-Technical-Papers)
  - [Tool page](http://mrg.doc.ic.ac.uk/tools/godel-checker/), sources: [godel-checker](https://bitbucket.org/MobilityReadingGroup/godel-checker) and [Go frontend](https://github.com/nickng/gospal)

- Finding The Greedy, Prodigal, and Suicidal Contracts at Scale (Ivica Nikolic, Aashish Kolluri, Ilya Sergey, Prateek Saxena, Aquinas Hobor)
  - [pdf](https://arxiv.org/abs/1802.06038) "To implement the validating framework, we added a new functionality to the official go-ethereum package [20] which allows us to fork the Ethereum main chain at a block height of our choice."

- State of Mutation Testing at Google (Goran Petrovic and Marko Ivankovic)
  - https://research.google.com/pubs/pub46584.html

- Index Data Structure, Functionality and Microservices in Thematic Virtual Museums (Sajarwo Anggai) (Ph.D. thesis)
  - http://vestnik.spbu.ru/html18/s10/s10v1/04.pdf

- "Two-Phase Dynamic Analysis of Message-Passing Go Programs based on Vector Clocks" (M. Sulzmann, K. Stadtmueller)
  - [arxiv](https://arxiv.org/abs/1807.03585)

- "Revisiting the Vector Space Model: Sparse Weighted Nearest-Neighbor Method for Extreme Multi-Label Classification" (Tatsuhiro Aoshima, Kei Kobayashi, Mihoko Minami)
  - [arxiv](https://arxiv.org/abs/1802.03938)

- "GEEC: Scalable, Efficient, and Consistent Consensus for Blockchains" (Xusheng Chen, Shixiong Zhao, Cheng Wang, Senran Zhang, Heming Cui)
  - [arxiv](https://arxiv.org/abs/1808.02252)

- "Dependability in a Multi-tenant Multi-framework Deep Learning as-a-Service Platform" (Scott Boag, Parijat Dube, Kaoutar El Maghraoui, Benjamin Herta, Waldemar Hummer, K. R. Jayaram, Rania Khalaf, Vinod Muthusamy, Michael Kalantar, Archit Verma)
  - [arxiv](https://arxiv.org/abs/1805.06801)
  - [github](https://github.com/IBM/FfDL)

- DRONE: a Distributed Subgraph-Centric Framework for Processing Large Scale Power-law Graphs
  - [arxiv](https://arxiv.org/abs/1812.04380)

- Reducing Metadata Leakage from Encrypted Files and Communication with PURBs
  - [arxiv](https://arxiv.org/abs/1806.03160)



## 2017

- Gorums: Towards new abstractions for implementing quorum-based systems. Tormod Erevik Lea, Leander Jehl, and Hein Meling. In Kisung Lee and Ling Liu, editors, 37th IEEE International Conference on Distributed Computing Systems, ICDCS 2017, Atlanta, GA, USA, June 5-8, 2017, pages 2380--2385. IEEE Computer Society, 2017
  - [doi:10.1109/ICDCS.2017.166](http://dx.doi.org/10.1109/ICDCS.2017.166)
  - [Gorums on GitHub](https://github.com/relab/gorums)
- Go-HEP: writing concurrent software with ease and Go (S. Binet)
  - [doi:10.1088/1742-6596/1085/5/052012](https://doi.org/10.1088/1742-6596/1085/5/052012)
  - [arXiV:1808.06529](https://arxiv.org/abs/1808.06529)
  - https://go-hep.org
- RDFIO: extending Semantic MediaWiki for interoperable biomedical data management (Samuel Lampa, Egon Willighagen, Pekka Kohonen, Ali King, Denny Vrandečić, Roland Grafström, Ola Spjuth) Journal of Biomedical Semantics ( Volume: 8, Issue: 35 )
  - [DOI: 10.1186/s13326-017-0136-y](https://doi.org/10.1186/s13326-017-0136-y)
  - The rdf2smw commandline tool, for batch conversion from RDF to Semantic MediaWiki facts in MediaWiki XML dump format, is written in Go
  - [github.com/rdfio/rdf2smw](https://github.com/rdfio/rdf2smw)
  - [godoc](https://godoc.org/github.com/rdfio/rdf2smw)
  - Keywords: Semantic MediaWiki, Semantic Web, RDF
- Construction and first tests of an in-beam PET demonstrator dedicated to the ballistic control of hadrontherapy treatments with 65 MeV protons (E Busato et al.)  IEEE Transactions on Radiation and Plasma Medical Sciences ( Volume: PP, Issue: 99 )
  - [DOI: 10.1109/TRPMS.2017.2780447](https://doi.org/10.1109/TRPMS.2017.2780447)
  - Monitoring system + parts of the DAQ in Go
  - Keywords: Detectors, Particle beams, Protons, Ions, Plasmas, Structural beams, Monitoring
- Let's Go: a Data-Driven Multi-Threading Support (Alberto Scionti,Somnath Mazumdar) CF'17 Proceedings of the Computing Frontiers Conference 
  - [doi.org/10.1145/3075564.3075596](https://doi.org/10.1145/3075564.3075596)  _"... This paper proposes a first attempt to map goroutines on a data-driven based PXM. ..."_
  - Keywords:  Data-driven, Programming language, Multi-threading
- Estimating Mixture Entropy with Pairwise Distances (Artemy Kolchinsky, Brendan D. Tracey)
  - [arXiv](https://arxiv.org/abs/1706.02419)
  - [godoc](https://godoc.org/github.com/btracey/mixent)
- Towards Omnia: a Monitoring Factory for Quality-Aware DevOps (Marco Miglierina, Damian A. Tamburri)
  - [doi.org/10.1145/3053600.3053629](https://doi.org/10.1145/3053600.3053629) ICPE '17 Companion
  - [github.com/mmiglier/omnia](https://github.com/mmiglier/omnia) (Go: 52.8% )
  - Keywords: Monitoring, Monitoring Management, Monitoring Factory, Monitoring Interface, Monitoring Infrastructure as Code, Monitoring Configuration as Code
- Copy-on-Reference File Mechanism Extends Scope of Dynamic Reconfiguration (Jeremy Krach) thesis
  - [pdf](http://honors.cs.umd.edu/uploads/thesis/file/189/Krach_Jeremy_Thesis.pdf)
  - [github.com/krockpot/lazyfs](https://github.com/krockpot/lazyfs) _"Lazy file retrieval for process migration."_
- An event model for phylogenetic biogeography using explicitly geographical ranges (J. Salvador Arias)
  - http://onlinelibrary.wiley.com/doi/10.1111/jbi.13024/full
  - Computer implementation (EVS written in Go) : [github.com/js-arias/evs](https://github.com/js-arias/evs) _"Evs is a tool for phylogenetic biogeography.
"_
- Feasibility of reusable continuous thrust spacecraft for cargo resupply missions to Mars (C. B. Rabotin) thesis
  - [pdf](http://hanspeterschaub.info/Papers/grads/ChristopherRabotin.pdf)
  - [github.com/ChristopherRabotin/smd](https://github.com/ChristopherRabotin/smd) Space Mission Design - A SPICE-enhanced continuous thrust interplanetary mission propagator and vizualizer
  - Keywords: space-mission interplanetary-missions celestial-bodies astrodynamics orbit propagation spice
- Performance testing of open-source HTTP web frameworks in an API (Michael A.P. Domingues) DSIE’17
  - https://paginas.fe.up.pt/~prodei/dsie17/DSIE17_Proceedings.pdf#page=18
  - Keywords: Revel, Gin and Echo, Performance testing, API, Web frameworks, Apache benchmark

- Method of auto-configuration for corporate proxies (Andrés Abelardo Villarroel Acosta, Carlos Enrique Montenegro Marín, Paulo Alonso Gaona García, Yuri Vanessa Nieto Acevedo) Ingeniería solidaria, 2017 
  - https://revistas.ucc.edu.co/index.php/in/article/view/1723
  - https://github.com/andresvia/udpac
  - Keywords: Proxy Auto-configuration (PAC), Web Proxy Auto-Discovery Protocol (WPAD), Dynamic Host Configuration Protocol (DHCP), Standard Time.
- NucAmino: a nucleotide to amino acid alignment optimized for virus gene sequences ( Philip L. Tzou, Xiaoqiu Huang, Robert W. Shafer ) BMC Bioinformatics (2017) 18: 138. 
  - [DOI: 10.1186/s12859-017-1555-6](https://link.springer.com/article/10.1186/s12859-017-1555-6) _"... NucAmino is written in the computer language Go ..."_
  - [github.com/hivdb/NucAmino](https://github.com/hivdb/NucAmino) ( Go 94.4% )
  - Keywords: Sequence alignment, Viruses, HIV-1, Drug resistance, Open source
- Idiomatic and Reproducible Software Builds using Containers for Reliable Computing (Jonas Weber) Master’s Thesis
  - [arXiv:1702.02999v1 cs.SE 9 Feb 2017](https://arxiv.org/abs/1702.02999), [pdf](https://arxiv.org/pdf/1702.02999.pdf)
  - [github.com/thriqon/thesis-supplement](https://github.com/thriqon/thesis-supplement)

- Structured I/O streams in Clive: a toolbox approach for wide area network computing ( Francisco J. Ballesteros )
  - [DOI: 10.1186/s13174-016-0054-8 OPEN ACCESS](http://jisajournal.springeropen.com/articles/10.1186/s13174-016-0054-8)  _" ... Clive is a system written in Go ..."_
  - [Clive related research](http://lsub.org/ls/research.html) 
  - [Clive source](http://lsub.org/ls/clive.html) _"...Clive is an operating system designed to work in distributed and cloud computing environments. ..."_
  - Keywords: Streams, Input/Output, Operating system, Distributed systems, Cloud computing 
- Towards Practical Default-On Multi-Core Record/Replay ( Ali José Mashtizadeh, Tal Garfinkel, David Terei, David Mazières, Mendel Rosenblum)  draft ,  ASPLOS 2017
  - [Draft – Accepted at ASPLOS 2017 - PDF](http://mashtizadeh.org/papers/asplos17-castor-draft.pdf) _"...Castor currently supports applications written in C, C++, and Go on FreeBSD...., ...  For Go, we evaluate, Caddy ... "_
- Comparing MapReduce and Pipeline Implementations for Counting Triangles ( Edelmira Pasarella, Maria-Esther Vidal, Cristina Zoltan)
  - [arXiv:1701.03318 cs.DC](https://arxiv.org/abs/1701.03318)
  - [pdf](https://arxiv.org/pdf/1701.03318.pdf) _"... an ad-hoc version of MapReduce are implemented in the language Go ..."_
- Fencing off Go: Liveness and Safety for Channel-based Programming (J. Lange, N. Ng, B. Toninho, N. Yoshida), POPL 2017
  - [doi: 10.1145/3009837.3009847](http://dl.acm.org/citation.cfm?id=3009847)
  - [Tool page](http://mrg.doc.ic.ac.uk/tools/gong/), [code](https://github.com/nickng/gong)
- Design and Implementation of Concurrent C0 (Willsey, Prabhu, Pfenning)
  - https://arxiv.org/abs/1701.04929
- Automated Identification of Security Issues from Commit Messages and Bug Reports (Yagin Zhou, Asankhaya Sharma), FSE 2017
  - [doi: 10.1145/3106237.3117771](http://dl.acm.org/citation.cfm?doid=3106237.3117771)
- Reconstructing Program Semantics from Go Binaries (Engelke)
  - http://home.in.tum.de/~engelke/pubs/1709-ma.pdf
- An Attempt at Reducing Costs of Disk I/O in Go (Wilson, Mutschlechner)
  - http://pages.cs.wisc.edu/~riccardo/assets/diskio.pdf
- Go-RealTime: A Lightweight Framework for Multiprocessor Real-Time System in User Space (Fang, Luo, Anwar, Zhuang, Gupta)
  - http://sigbed.seas.upenn.edu/archives/2017-11/paper7.pdf
- "Secure and Trustable Electronic Medical Records Sharing using Blockchain" (Alevtina Dubovitskaya, Zhigang Xu, Samuel Ryu, Michael Schumacher, Fusheng Wang)
  - [arxiv](https://arxiv.org/abs/1709.06528)
- "Towards a More Reliable and Available Docker-based Container Cloud" (Mudit Verma, Mohan Dhawan)
  - [arxiv](https://arxiv.org/abs/1708.08399)


## 2016
- Atom: Horizontally Scaling Strong Anonymity (Albert Kwon, Henry Corrigan-Gibbs, Srinivas Devadas, Bryan Ford)
  - [arXiv:1612.07841 cs.CR](https://arxiv.org/abs/1612.07841) _"...We implemented an Atom prototype in Go in approximately 3,500 lines of code, ..."_
- The Case for Reconfiguration without Consensus: Comparing Algorithms for Atomic Storage (Leander Jehl, Hein Meling) 
  - [pdf](http://drops.dagstuhl.de/opus/volltexte/2017/7100/pdf/LIPIcs-OPODIS-2016-31.pdf) 
  - [github.com/relab/smartmerge](https://github.com/relab/smartmerge) implemented in golang
- Flower :  Workflow management and heat-aware scheduling for modern cloud infrastructures (Robert Carosi,
Boris Mattijssen) bachelor thesis,
  - [abstract](http://repository.tudelft.nl/islandora/object/uuid:fd1a2aea-84d0-42cc-8043-23a182748f8c),  [pdf](http://repository.tudelft.nl/islandora/object/uuid:fd1a2aea-84d0-42cc-8043-23a182748f8c/datastream/OBJ/view), Keywords: container, workflow, virtualization, scheduling, flower, kubernetes
- Implementing a web-based bookingsystem using Go ( Vu, Phi-Long )  Independent thesis Basic level 
  - [abstract](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1070267&dswid=784), [pdf](http://www.diva-portal.org/smash/get/diva2:1070267/FULLTEXT01.pdf) ; Keywords: Booking System, Go, Golang, REST, XSS, XSRF
- Parallelization of the corpus manager’s time-consuming operations (Bc. Radoslav Rábara ) Master's Thesis, Masaryk University
  - [pdf](http://www.itspy.cz/wp-content/uploads/2016/11/IT_SPY_2016_paper_60.pdf) ; Keywords: Manatee, text corpora, Go, text compression, compression of integers, time-consuming operations, parallelization, MapReduce, Glow, distributed computing, data format, cluster, scalability
- Cyber Security Exercise Modeling & Tracking (Joonas Greis) Bachelor’s thesis
  - [pdf](https://www.theseus.fi/bitstream/handle/10024/120054/Thesis_rellu.pdf) _"... RESTful API was written with Golang using Go-Json-Rest package ..."_
- Scalable Byzantine Consensus via Hardware-assisted Secret Sharing (Jian Liu, Wenting Li, Ghassan O. Karame, N. Asokan) 
  - [arXiv:1612.04997 cs.CR](https://arxiv.org/abs/1612.04997) ;   _"... Our implementation is based on Golang ..."_  ; [pdf](https://arxiv.org/pdf/1612.04997v1.pdf) 
- Fast and Reliable Byzantine Fault Tolerance (Eric Scott Freeman) Master's thesis in Computer science
  - [link](http://hdl.handle.net/11250/2413908), [pdf]( https://brage.bibsys.no/xmlui/bitstream/handle/11250/2413908/Freeman_Eric.pdf?sequence=1)
- Formal verification of concurrency in go (Anuchit Prasertsang, Denduang Pradubsuwun)
  - [DOI: 10.1109/JCSSE.2016.7748882](http://dx.doi.org/10.1109/JCSSE.2016.7748882)
- Therapeutic target discovery using Boolean network attractors: updates from kali ( Arnaud Poret ) ( Quantitative Biology > Molecular Networks) 
  - [arXiv:1611.03144v1 q-bio.MN](https://arxiv.org/abs/1611.03144v1)
  - [github.com/arnaudporet/kali](https://github.com/arnaudporet/kali) [Go 100.0%]
- Information Flow Analysis for Go ( Eric Bodden, Ka I. Pun, Martin Steffen, Volker Stolz, Anna-Katharina Wickert)
  - [10.1007/978-3-319-47166-2_30](http://link.springer.com/chapter/10.1007/978-3-319-47166-2_30) 
- A Productivity Checker for Logic Programming (E. Komendantskaya, P. Johann, M. Schmidt )
  - [arXiv:1608.04415 cs.PL](https://arxiv.org/abs/1608.04415) 
  - project page: http://www.macs.hw.ac.uk/~ek19/CoALP/
- A novel algorithm for detecting multiple covariance and clustering of biological sequences
( Wei Shen & Yan Li)   ( Coevolution, Computational models ) 
  - http://www.nature.com/articles/srep30425 , doi:10.1038/srep30425
  - Algorithm implementation (golang - only binary ) : http://yanlilab.github.io/fastcov/
- Architecture of the Hyperledger Blockchain Fabric (Christian Cachin)
  - [pdf](https://www.zurich.ibm.com/dccl/papers/cachin_dccl.pdf)
  - [code]( https://github.com/hyperledger/fabric/)
- Reimagining the Programming Experience ( Mehrdad Afshari , dissertation) GoClr
  - [pdf](https://mehrdad.afshari.me/publications/dissertation.pdf)
- MapReduce vs. Pipelining Counting Triangles (Edelmira Pasarella, Maria-Esther Vidal,and Cristina Zoltan) 
  - [pdf](http://ceur-ws.org/Vol-1644/paper33.pdf)
- Parametric Polymorphism in the Go Programming Language (Matthew Allen) University of Texas, 
Turing Scholars honors thesis 
  - [pdf](http://apps.cs.utexas.edu/tech_reports/reports/tr/TR-2231.pdf)
  - [code](https://github.com/Matt343/llgo) ( LLGO based ) 
- Static Trace-Based Deadlock Analysis for Synchronous Mini-Go ( Kai Stadtmüller, Martin Sulzmann, and Peter Thiemann ) 
  - [pdf](http://www.home.hs-karlsruhe.de/~suma0002/publications/TraceBasedDeadlockAnalysisMiniGo.pdf)
  - [code](https://github.com/KaiSta/gopherlyzer) -  first beta implementation : gopherlyzer
- Continuous Query-Based Syndication: Distributed, Expressive Messaging for the IoT( Gabriel Fierro, Erik Krogen ) 
  - [pdf](https://people.eecs.berkeley.edu/~kubitron/courses/cs262a-S16/projects/reports/project1_report.pdf), [motivation](https://github.com/gtfierro/cs262-project/blob/master/Motivation.md)
  - [code](https://github.com/gtfierro/cs262-project) ( Go and Python implementation )
- Privacy, Discovery, and Authentication for the Internet of Things (Wu, Taly, Shankar, Boneh)
  - [arxiv](https://arxiv.org/abs/1604.06959)
  - [code](https://vanadium.github.io/)
- Static Deadlock Detection for Concurrent Go by Global Session Graph Synthesis (Ng, Yoshida)
  - [pdf](http://www.doc.ic.ac.uk/~cn06/pub/2016/dingo/main.pdf)
  - [code](https://github.com/nickng/dingo-hunter)
- A Small-Step Semantics of a Concurrent Calculus with Goroutines and Deferred Functions ( Martin Steffen )
  - [springer link](http://link.springer.com/chapter/10.1007%2F978-3-319-30734-3_26)
- Butterfield, Ellis H., "Fog Computing with Go: A Comparative Study" (2016). CMC Senior Theses. Paper 1348.
  - http://scholarship.claremont.edu/cmc_theses/1348
- An Implementation and Analysis of a Kernel Network Stack in Go with the CSP Style (Harshal Sheth, Aashish Welling) 
  - [arXiv:1603.05636 cs.OS](http://arxiv.org/abs/1603.05636 )
- PAS-MC: Privacy-preserving Analytics Stream for the Mobile Cloud (Joy, Gerla)
  - [arXiv:1604.04892 cs.CR](https://arxiv.org/abs/1604.04892)
- Developing an Ethereum Blockchain Application (Triantafyllidis)
  - [pdf](https://homepages.staff.os3.nl/~delaat/rp/2015-2016/p53/report.pdf)
- Identifying and characterizing Sybils in the Tor network (Winter, Ensafi, Loesing, and Feamster)
  - [pdf](https://nymity.ch/sybilhunting/pdf/sybilhunting.pdf)
  - [code](https://github.com/NullHypothesis/sybilhunter)
- A Distributed Implementation of the Graph Database System: DGraph
  - [pdf](https://www.dropbox.com/s/7h4ytak39r2pdun/Ashwin_Thesis.pdf?dl=0)
- Browsix: Bridging the Gap Between Unix and the Browser (Powers, Vilk, Berger)
  - https://arxiv.org/abs/1611.07862
- Verification of Goroutines using Why3 (Schoolderman)
  - https://www.ru.nl/publish/pages/769526/marc_schoolderman.pdf
- Detection of Bugs and Code Smells through Static Analysis of Go Source Code (Bergersen)
  - https://www.duo.uio.no/bitstream/handle/10852/53050/bergersen_msc.pdf
- BTrDB: Optimizing Storage System Design for Timeseries Processing (Andersen, Culler)
  - https://www.usenix.org/node/194399
- Risk Factor Disclosures: Do Managers and Markets Speak the Same Language?
  - https://www.sec.gov/comments/s7-06-16/s70616-369.pdf

## 2015
- Tinzenite: Encrypted Peer to Peer File Synchronization via the Tox Protocol (Tamino P.S.M. Hartmann) (Master thesis at Ulm University) 
  - [pdf](http://dbis.eprints.uni-ulm.de/1334/1/ma_final_hartmann.pdf)
  - [github.com/tinzenite](https://github.com/tinzenite)
- Blade: A Data Center Garbage Collector (Terei, Levy)
  - [arxiv:1504.02578 cs.DC](https://arxiv.org/abs/1504.02578)
- Flywheel: Google's Data Compression Proxy for the Mobile Web (Agababov, Buettner, Chudnovsky, Cogan, Greenstein, McDaniel, Piatek, Scott, Welsh, Yin)
  - [pdf](http://research.google.com/pubs/pub43447.html)
  - [Rewriting a large production system in Go](http://matt-welsh.blogspot.com/2013/08/rewriting-large-production-system-in-go.html)
- A Machine Learning Strategy to Assist Turbulence Model Development (Brendan Tracey, Karthik Duraisamy, Juan J. Alonso)
  - http://arc.aiaa.org/doi/abs/10.2514/6.2015-1287
-  Implementing an intelligent version of the classical sliding-puzzle game for unix terminals using Golang's concurrency primitives ( Pravendra Singh )
   - [arxiv:1503.08345 cs.AI](http://arxiv.org/abs/1503.08345 )
- Keeping Authorities "Honest or Bust" with Decentralized Witness Cosigning (Syta, Tamas, Visher, Wolinsky, Jovanovic, Gasser, Gailly, Khoffi, Ford)
   - [arxiv:1503.08768 cs.CR](https://arxiv.org/abs/1503.08768)
   - [code](https://github.com/dedis/cothority), [code](https://github.com/dedis/cosi)
- Message Passing for Programming Languages and Operating Systems (Martynas Pumputis ) Master’s Thesis
   - [pdf](http://e-collection.library.ethz.ch/eserv/eth:48404/eth-48404-01.pdf)
- Type inference for Go (Emin Gigovic, Philip Malmros )
   - [pdf](http://fileadmin.cs.lth.se/cs/Education/EDAN70/CompilerProjects/2015/Reports/GigovicMalmros.pdf)
- Open-Source, Platform-Independent Library and Online Scripting Environment for Accessing Thermo Scientific RAW Files. (Kelchtermans, Silva, Argentini, Staes, Vandenbussche, Laukens, Valkenborg, Martens)
  - https://www.ncbi.nlm.nih.gov/pubmed/26477298
- Evaluation of performance and productivity metrics of potential programming languages in the HPC environment ( Bachelor Thesis ; Florian Wilkens ) -  ( Go, Rust, C, OpenStreetMap )
  - [github-code](https://github.com/MrFloya/thesis-ba) , [pdf](https://github.com/MrFloya/thesis-ba/raw/master/tex/thesis.pdf)
- Concurrent Processing of Text Corpus Queries (Rábara, Rychlý)
  - https://www.sketchengine.co.uk/wp-content/uploads/Concurrent_Processing_2015.pdf
- Automatic Memory Management Techniques for the Go Programming Language (Davis) (Ph.D. thesis)
  - https://minerva-access.unimelb.edu.au/handle/11343/58707
- Design Muntoi Web-based Framework and Search Engine Analytics for Thematic Virtual Museums (Sajarwo Anggai) (Ph.D. thesis)
  - http://ieeexplore.ieee.org/document/7516334/
- A Search Engine Backed by Internet-Wide Scanning (Durumeric, Adrian, Mirian, Bailey, Halderman)
  - https://censys.io/static/censys.pdf
- An Extract Function Refactoring for the Go Language (Arasu)
  - https://etd.auburn.edu/bitstream/handle/10415/4835/Steffi_Gnanaprakasa_MSThesis.pdf
- Compositional Decompilation using LLVM IR (BSc thesis, Robin Eklind)
  - http://uu.diva-portal.org/smash/record.jsf?pid=diva2%3A911797&dswid=-6147
  - [code](https://github.com/decomp/decomp)
  - [pdf](https://github.com/decomp/doc/raw/master/report/compositional_decompilation/compositional_decompilation.pdf)
- "U-root: A Go-based, Firmware Embeddable Root File System with On-demand Compilation" (Minnich, Mirtchovski)
  - [pdf](https://www.usenix.org/system/files/conference/atc15/atc15-paper-minnich.pdf)
  - [code](https://github.com/u-root/u-root)
## 2014
- PARAGON: an approach for parallelization of power system contingency analysis using Go programming language
  - http://onlinelibrary.wiley.com/doi/10.1002/etep.1999/full
- A Study of Successive Over-relaxation Method Parallelization Over Modern HPC Languages (Mittal)
  - [arxiv:1401.0763 cs.DC](https://arxiv.org/abs/1401.0763)
  - [code](https://github.com/sparsh0mittal/sor_serial_parallel_codes)
- There Is More Consensus in Egalitarian Parliaments (Moraru, Andersen, Kaminsky)
  - [pdf](https://www.cs.cmu.edu/~dga/papers/epaxos-sosp2013.pdf)
  - [code](https://github.com/efficient/epaxos)
  - [Experience with ePaxos: Systems Research using Go](https://da-data.blogspot.com/2013/10/experience-with-epaxos-systems-research.html)
- Research Problems of Implementing Go
  - https://talks.golang.org/2014/research.slide  (rsc)
  - https://talks.golang.org/2014/research2.slide (dvyukov)
- bíogo: a simple high-performance bioinformatics toolkit for the Go language (D. Kortschak, D. Adelson)
  - [pdf](http://biorxiv.org/content/early/2014/05/12/005033)
- P2S: A Fault-Tolerant Publish/Subscribe Infrastructure (Chang, Duan, Meling, Peisert, Zhang)
  - [pdf](http://cs.unc.edu/~haibin/p2s.pdf)
- Generating a Google Go framework from an Uppaal model (Dekker)
  - [pdf](https://www.cs.ru.nl/bachelorscripties/2014/Jip_Dekker___4122100___Generating_Google_Go_framework_from_Uppaal_models.pdf)
- Using the Go Programming Language in Practice (Westrup, Pettersson)
  - [pdf](https://www.researchgate.net/publication/312490994_Using_the_Go_Programming_Language_in_Practice)
- A Language Support for Exhaustive Fault-Injection in Message-Passing System Models (Suzuki, Watanabe)
  - [arXiv:1411.3793 cs.SE](https://arxiv.org/abs/1411.3793)
- Big Learning with Bayesian Methods
  - [arXiv:1411.6370 cs.LG](https://arxiv.org/abs/1411.6370)
- Be General and Don't Give Up Consistency in Geo-Replicated Transactional Systems
  - [PDF](http://hyflow.org/pubs/opodis14-alvin.pdf)
  - Project page: [Hyflow](http://www.hyflow.org/hyflow-go/index.html)
- The design and verification of Mumax3 (Vansteenkiste, Leliaert, Dvornik, Garcia-Sanchez, Van Waeyenberge)
  - https://arxiv.org/abs/1406.7635
  - https://github.com/mumax/3
- Building Reliable and Practical Byzantine Fault Tolerance (Duan)
  - http://sduan.informationsystems.umbc.edu/files/2014-SisiDuan-dissertation.pdf

## 2013
- GoPar: Automatic Loop Parallelization of Go Programs (Wetherbee)
  - [pdf](https://docs.google.com/file/d/0B6tFaBl5qV_gNmpRTnJkcEo4a2M/edit)
  - [code](https://github.com/wetherbeei/gopar)
- SCTP in Go ( Olivier Van Acker )
  - Keywords: Stream Control Transmission Protocol (SCTP); Transmission Control Protocol (TCP); Go; Networking;
  - [pdf](https://2013.asiabsdcon.org/papers/abc2013-P7A-paper.pdf)  
- Benchmarking Usability and Performance of Multicore Languages ( Sebastian Nanz, Scott West, Kaue Soares da Silveira, Bertrand Meyer)
  - [arXiv:1302.2837 cs.DC](https://arxiv.org/abs/1302.2837)
- Examining the Expert Gap in Parallel Programming (Sebastian Nanz, Scott West, Kaue Soares da Silveira)
  - [pdf](http://se.inf.ethz.ch/people/west/expert-gap-europar-2013.pdf)
- Acropolis: aggregated client request ordering by Paxos (Jothen)
  - https://brage.bibsys.no/xmlui//handle/11250/181825
- Implementation and experimental evaluation of live replacement and reconfiguration (Lea)
  - https://brage.bibsys.no/xmlui//handle/11250/181813
- Exploiting Parallelism in Coalgebraic Logic Programming (Komendantskaya, Schmidt, Heras)
  - https://arxiv.org/abs/1312.4454
- Parallel Pattern Discovery (Egon Elbre), Master's Thesis, University of Tartu
  - [pdf](http://egonelbre.github.io/spexs2/Thesis.pdf)
  - [code](https://github.com/egonelbre/spexs2)

## 2012
- Time Warp on the Go (D'Angelo, Ferretti, Marzolla)
  - [arxiv:1206.2772 cs.DC](https://arxiv.org/abs/1206.2772)
- Can Go address the multicore issues of today and the manycore problems of tomorrow? (S. Binet)
  - [pdf](http://iopscience.iop.org/article/10.1088/1742-6596/368/1/012017)
- GoCxx: a tool to easily leverage C++ legacy code for multicore-friendly Go libraries and frameworks (S. Binet)
  - [pdf](http://iopscience.iop.org/article/10.1088/1742-6596/396/5/052012)
- The Buffered π-Calculus: A Model for Concurrent Languages (Deng, Zhang, Deng, Zhong)
  - [arxiv:1212.6183 cs.LO](https://arxiv.org/abs/1212.6183)
- Analysis of the Go runtime scheduler (Neil Deshpande,Erica Sponsler,Nathaniel Weiss)
  - [pdf](http://www1.cs.columbia.edu/~aho/cs6998/reports/12-12-11_DeshpandeSponslerWeiss_GO.pdf)
- A Comparative Study of Programming Models for Concurrency ( Kaue Soares da Silveira) – Porto Alegre: COMGRAD CIC UFRGS, 2012.  Final Report (Bachelor)
  - [pdf](ftp://ftp.inf.ufrgs.br/pub/geyer/Alunos/KaueSilveira/TG-ComparacaoLinguagensConcorrencia-kaue_soares_da_silveira.pdf)
- Debian Code Search (Stapelberg)
  - [pdf](https://codesearch.debian.net/research/bsc-thesis.pdf)
- Go’s Concurrency Constructs on the SCC (Prell, Rauber)
  - [pdf](https://hal.inria.fr/file/index/docid/718924/filename/MARC6_Gos-Concurrency-Constructs-on-the-SCC.pdf)
- Comparing Parallel Performance of Go and C++ TBB on a Direct Acyclic Task Graph Using a Dynamic Programming Problem (Serfass, Tang)
  - http://www.ualr.edu/pxtang/papers/ACMSE12-comparing.pdf


## 2011
- ng: What next-generation languages can teach us about HENP frameworks in the manycore era (S. Binet)
  - [pdf](http://iopscience.iop.org/article/10.1088/1742-6596/331/4/042002)
- Serving Web Content with Dynamic Process Networks in Go (James Whitehead II)
  - [DOI: 10.3233/978-1-60750-774-1-209](http://dx.doi.org/10.3233/978-1-60750-774-1-209)
  - [pdf](http://www.cs.ox.ac.uk/people/jim.whitehead/cpa2011-draft.pdf)

## 2010
- GoHotDraw: Evaluating the Go Programming Language with Design Patterns (Schmager, Cameron, Noble)
  - [pdf](http://www.doc.ic.ac.uk/~ncameron/papers/schmager_plateau10.pdf)
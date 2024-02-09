<h1 align="center"> Awesome-Open-Knowledge-Graphs </a></h2>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for the latest update.</h5>

<h5 align="center">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub issues](https://img.shields.io/github/issues/Yang233666/Awesome-Open-Knowledge-Graphs)](https://github.com/Yang233666/Awesome-Open-Knowledge-Graphs/issues)
[![GitHub forks](https://img.shields.io/github/forks/Yang233666/Awesome-Open-Knowledge-Graphs)](https://github.com/Yang233666/Awesome-Open-Knowledge-Graphs/network)
[![GitHub stars](https://img.shields.io/github/stars/Yang233666/Awesome-Open-Knowledge-Graphs)](https://github.com/Yang233666/Awesome-Open-Knowledge-Graphs/stargazers)

</h5>

> A collection of important **Open Knowledge Graph (OKG)** resources: research papers, code, data, applications, etc. 
This collection is not limited to Open Knowledge Graphs but also includes their downstream applications.

> We will try to make this list updated frequently. If you find any error or any missed paper, please don't hesitate to open issues or pull requests.


## Table of contents

- [Introduction to Open Knowledge Graphs](#introduction-to-open-knowledge-graphs)
- [Papers by venues](#papers-by-venues)
  * [2022](#2022)
  * [2021](#2021)
  * [2020](#2020)
  * [2019](#2019)
  * [2018](#2018)
  * [2014](#2014)
- [Papers by categories](#papers-by-categories)
  * [Survey Papers](#survey-papers)
  * [Evaluation](#evaluation)
  * [Open Knowledge Graph Canonicalization](#open-knowledge-graph-canonicalization)
  * [Open Knowledge Graph Link Prediction](#open-knowledge-graph-link-prediction)
  * [Open Knowledge Graph Reasoning](#open-knowledge-graph-reasoning)
  * [Open Knowledge Graph Alignment](#open-knowledge-graph-alignment)
  * [OKGs for downstream applications](#okgs-for-downstream-applications)
    + [Entity and Relation Linking](#entity-and-relation-linking)
- [Slides](#slides)
- [Talks](#talks)
- [Code](#code)
- [Data](#data)
  * [OIE corpora](#oie-corpora)
- [Other Repos](#other-repos)



## Introduction to Open Knowledge Graphs

Open Information Extraction (OIE) systems aim to extract unseen relations and their arguments from unstructured text in unsupervised manner. In its simplest form, given a natural language sentence, they extract information in the form of a triple, consisted of subject (S), relation (R) and object (O).

Suppose we have the following input sentence:

    AMD, which is based in U.S., is a technology company.

An OIE system aims to make the following extractions:

    ("AMD"; "is based in"; "U.S.")
    ("AMD"; "is"; "technology company")

## Papers by venues
   
### 2022

[SIGKDD' 2022] **Multi-View Clustering for Open Knowledge Base Canonicalization** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539449) | [Code](https://github.com/Yang233666/CMVC) | [Video](https://dl.acm.org/doi/10.1145/3534678.3539449)]

_Wei Shen, Yang Yang, Yinan Liu_

### 2021

[SIGMOD' 2021] **Joint Open Knowledge Base Canonicalization and Linking** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3448016.3452776) | [Code](https://github.com/JOCL-repo/JOCL) | [Video](https://dl.acm.org/doi/10.1145/3448016.3452776)]

_Yinan Liu, Wei Shen, Yuanfei Wang, Jianyong Wang, Zhenglu Yang, Xiaojie Yuan_

[ICDE' 2021] **CaSIE: Canonicalize and Informative Selection of the OpenIE system** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458825)]

_Hao Xin, Xueling Lin, Lei Chen_

[ACL' 2021] **OKGIT: Open Knowledge Graph Link Prediction with Implicit Types** [[Paper](https://aclanthology.org/2021.findings-acl.225.pdf) | [Code](https://github.com/Chandrahasd/OKGIT) | [Video](https://aclanthology.org/2021.findings-acl.225.mp4)]

_Chandrahas, Partha Pratim Talukdar_
    
[EMNLP' 2021] **Open Knowledge Graphs Canonicalization using Variational Autoencoders** [[Paper](https://aclanthology.org/2021.emnlp-main.811.pdf) | [Code](https://github.com/IBM/Open-KG-canonicalization) | [Video](https://aclanthology.org/2021.emnlp-main.811.mp4)]

_Sarthak Dash, Gaetano Rossiello, Nandana Mihindukulasooriya, Sugato Bagchi, Alfio Gliozzo_

### 2020

[VLDB' 2020] **KBPearl: A Knowledge Base Population System Supported by Joint Entity and Relation Linking** [[Paper](http://www.vldb.org/pvldb/vol13/p1035-lin.pdf) | [Code](https://hkustconnect-my.sharepoint.com/personal/xlinai_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos%2Fkbpearl%5Fdemo%2Ezip&parent=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos&ga=1) | [Readme](https://hkustconnect-my.sharepoint.com/personal/xlinai_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos%2FKBPEARL%5FREADME%2Emd&parent=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos&ga=1)]

_Xueling Lin, Haoyang Li, Hao Xin, Zijian Li, Lei Chen_
   
[ACL' 2020] **Can We Predict New Facts with Open Knowledge Graph Embeddings? A Benchmark for Open Link Prediction** [[Paper](https://aclanthology.org/2020.acl-main.209.pdf) | [Code](https://github.com/samuelbroscheit/open_knowledge_graph_embeddings) | [Resources](https://www.uni-mannheim.de/dws/research/resources/olpbench/) | [Video](https://slideslive.com/38929433/can-we-predict-new-facts-with-open-knowledge-graph-embeddings-a-benchmark-for-open-link-prediction)]

_Samuel Broscheit, Kiril Gashteovski, Yanjie Wang, Rainer Gemulla_

[Eval4NLP@EMNLP' 2020] **On Aligning OpenIE Extractions with Knowledge Bases: A Case Study** [[Paper](https://aclanthology.org/2020.eval4nlp-1.14.pdf) | [Resources](https://www.uni-mannheim.de/dws/research/resources/opiec/) | [Video](https://slideslive.com/38939720/on-aligning-openie-extractions-with-knowledge-bases-a-case-study) | [Slides](https://www.uni-mannheim.de/media/Einrichtungen/dws/pi1/opiec/dsa-ota-talk-final.pdf)]

_Kiril Gashteovski, Rainer Gemulla, Bhushan Kotnis, Sven Hertling, Christian Meilicke_
      
[WISE' 2020] **MULCE: Multi-level Canonicalization with Embeddings of Open Knowledge Bases** [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-62005-9_23)]

_Tien-Hsuan Wu, Ben Kao, Zhiyong Wu, Xiyang Feng, Qianli Song, Cheng Chen_
   
[CoRR' 2020] **Canonicalizing Open Knowledge Bases with Multi-Layered Meta-Graph Neural Network** [[Paper](https://arxiv.org/pdf/2006.09610.pdf)]

_Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang_

[CoRR' 2020] **Language Models are Open Knowledge Graphs** [[Paper](https://arxiv.org/pdf/2010.11967.pdf)]

_Chenguang Wang, Xiao Liu, Dawn Song_

### 2019

[ICDE' 2019] **Canonicalization of Open Knowledge Bases with Side Information from the Source Text** [[Paper](https://ieeexplore.ieee.org/abstract/document/8731346) | [Code](https://hkustconnect-my.sharepoint.com/personal/xlinai_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos%2Ficde2019%5Fsist%5Fcode%2Ezip&parent=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos&ga=1) | [Dataset Description](https://heathersherry.github.io/ICDE2019_data.html)]

_Xueling Lin, Lei Chen_

[EMNLP' 2019].**CaRe: Open Knowledge Graph Embeddings** [[Paper](https://aclanthology.org/D19-1036.pdf) | [Code](https://github.com/malllabiisc/CaRE)]

_Swapnil Gupta, Sreyash Kenkre, Partha Talukdar_
   
[EMNLP' 2019] **Collaborative Policy Learning for Open Knowledge Graph Reasoning** [[Paper](https://www.aclweb.org/anthology/D19-1269.pdf) | [Code](https://github.com/INK-USC/CPL)]
 
_Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren_
   
[AKBC' 2019] **OPIEC: An Open Information Extraction Corpus** [[Paper](https://openreview.net/pdf?id=HJxeGb5pTm) | [Data + Resources](https://www.uni-mannheim.de/dws/research/resources/opiec/) | [Code (data reading)](https://github.com/uma-pi1/OPIEC) | [Code (pipeline)](https://github.com/uma-pi1/OPIEC-pipeline)]

_Kiril Gashteovski, Sebastian Wanner, Sven Hertling, Samuel Broscheit, Rainer Gemulla_
   
### 2018

[WWW' 2018] **CESI: Canonicalizing Open Knowledge Bases using Embeddings and Side Information** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3178876.3186030) | [Code](https://github.com/malllabiisc/cesi)]
  
_Shikhar Vashishth, Prince Jain, Partha Talukdar_

[CIKM' 2018] **Towards Practical Open Knowledge Base Canonicalization** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271707)]

_Tien-Hsuan Wu, Zhiyong Wu, Ben Kao, Pengcheng Yin_

### 2014

[CIKM' 2014] **Canonicalizing Open Knowledge Bases** [[Paper](https://suchanek.name/work/publications/cikm2014.pdf)]

_Luis Galárraga, Geremy Heitz, Kevin Murphy, Fabian M. Suchanek_



## Papers by categories


### Survey Papers


### Evaluation


### Open Knowledge Graph Canonicalization
   
[SIGKDD' 2022] **Multi-View Clustering for Open Knowledge Base Canonicalization** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539449) | [Code](https://github.com/Yang233666/CMVC) | [Video](https://dl.acm.org/doi/10.1145/3534678.3539449)]

_Wei Shen, Yang Yang, Yinan Liu_

[SIGMOD' 2021] **Joint Open Knowledge Base Canonicalization and Linking** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3448016.3452776) | [Code](https://github.com/JOCL-repo/JOCL) | [Video](https://dl.acm.org/doi/10.1145/3448016.3452776)]

_Yinan Liu, Wei Shen, Yuanfei Wang, Jianyong Wang, Zhenglu Yang, Xiaojie Yuan_

[EMNLP' 2021] **Open Knowledge Graphs Canonicalization using Variational Autoencoders** [[Paper](https://aclanthology.org/2021.emnlp-main.811.pdf) | [Code](https://github.com/IBM/Open-KG-canonicalization) | [Video](https://aclanthology.org/2021.emnlp-main.811.mp4)]

_Sarthak Dash, Gaetano Rossiello, Nandana Mihindukulasooriya, Sugato Bagchi, Alfio Gliozzo_

[WISE' 2020] **MULCE: Multi-level Canonicalization with Embeddings of Open Knowledge Bases** [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-62005-9_23)]

_Tien-Hsuan Wu, Ben Kao, Zhiyong Wu, Xiyang Feng, Qianli Song, Cheng Chen_
   
[CoRR' 2020] **Canonicalizing Open Knowledge Bases with Multi-Layered Meta-Graph Neural Network** [[Paper](https://arxiv.org/pdf/2006.09610.pdf)]

_Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang_

[ICDE' 2019] **Canonicalization of Open Knowledge Bases with Side Information from the Source Text** [[Paper](https://ieeexplore.ieee.org/abstract/document/8731346) | [Code](https://hkustconnect-my.sharepoint.com/personal/xlinai_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos%2Ficde2019%5Fsist%5Fcode%2Ezip&parent=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos&ga=1) | [Dataset Description](https://heathersherry.github.io/ICDE2019_data.html)]

_Xueling Lin, Lei Chen_

[WWW' 2018] **CESI: Canonicalizing Open Knowledge Bases using Embeddings and Side Information** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3178876.3186030) | [Code](https://github.com/malllabiisc/cesi)]
  
_Shikhar Vashishth, Prince Jain, Partha Talukdar_

[CIKM' 2018] **Towards Practical Open Knowledge Base Canonicalization** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271707)]

_Tien-Hsuan Wu, Zhiyong Wu, Ben Kao, Pengcheng Yin_

[CIKM' 2014] **Canonicalizing Open Knowledge Bases** [[Paper](https://suchanek.name/work/publications/cikm2014.pdf)]

_Luis Galárraga, Geremy Heitz, Kevin Murphy, Fabian M. Suchanek_

### Open Knowledge Graph Link Prediction

[ACL' 2021] **OKGIT: Open Knowledge Graph Link Prediction with Implicit Types** [[Paper](https://aclanthology.org/2021.findings-acl.225.pdf) | [Code](https://github.com/Chandrahasd/OKGIT) | [Video](https://aclanthology.org/2021.findings-acl.225.mp4)]

_Chandrahas, Partha Pratim Talukdar_
    
[ACL' 2020] **Can We Predict New Facts with Open Knowledge Graph Embeddings? A Benchmark for Open Link Prediction** [[Paper](https://aclanthology.org/2020.acl-main.209.pdf) | [Code](https://github.com/samuelbroscheit/open_knowledge_graph_embeddings) | [Resources](https://www.uni-mannheim.de/dws/research/resources/olpbench/) | [Video](https://slideslive.com/38929433/can-we-predict-new-facts-with-open-knowledge-graph-embeddings-a-benchmark-for-open-link-prediction)]

_Samuel Broscheit, Kiril Gashteovski, Yanjie Wang, Rainer Gemulla_

[EMNLP' 2019].**CaRe: Open Knowledge Graph Embeddings** [[Paper](https://aclanthology.org/D19-1036.pdf) | [Code](https://github.com/malllabiisc/CaRE)]

_Swapnil Gupta, Sreyash Kenkre, Partha Talukdar_

### Open Knowledge Graph Reasoning

[EMNLP' 2019] **Collaborative Policy Learning for Open Knowledge Graph Reasoning** [[Paper](https://www.aclweb.org/anthology/D19-1269.pdf) | [Code](https://github.com/INK-USC/CPL)]
 
_Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren_

### Open Knowledge Graph Alignment

[Eval4NLP@EMNLP' 2020] **On Aligning OpenIE Extractions with Knowledge Bases: A Case Study** [[Paper](https://aclanthology.org/2020.eval4nlp-1.14.pdf) | [Resources](https://www.uni-mannheim.de/dws/research/resources/opiec/) | [Video](https://slideslive.com/38939720/on-aligning-openie-extractions-with-knowledge-bases-a-case-study) | [Slides](https://www.uni-mannheim.de/media/Einrichtungen/dws/pi1/opiec/dsa-ota-talk-final.pdf)]

_Kiril Gashteovski, Rainer Gemulla, Bhushan Kotnis, Sven Hertling, Christian Meilicke_
   
### OKGs for downstream applications

OKG's output has been shown to be a useful input for many downstream tasks. In this section, several downstream tasks that benefited from OKG output are listed. 

#### Entity and Relation Linking

[ICDE' 2021] **CaSIE: Canonicalize and Informative Selection of the OpenIE system** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9458825)]

_Hao Xin, Xueling Lin, Lei Chen_

[VLDB' 2020] **KBPearl: A Knowledge Base Population System Supported by Joint Entity and Relation Linking** [[Paper](http://www.vldb.org/pvldb/vol13/p1035-lin.pdf) | [Code](https://hkustconnect-my.sharepoint.com/personal/xlinai_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos%2Fkbpearl%5Fdemo%2Ezip&parent=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos&ga=1) | [Readme](https://hkustconnect-my.sharepoint.com/personal/xlinai_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos%2FKBPEARL%5FREADME%2Emd&parent=%2Fpersonal%2Fxlinai%5Fconnect%5Fust%5Fhk%2FDocuments%2Fdemos&ga=1)]

_Xueling Lin, Haoyang Li, Hao Xin, Zijian Li, Lei Chen_


## Slides
* [\[pdf\] *"Compact Open Information Extraction on Large Corpora"*](https://www.uni-mannheim.de/media/Einrichtungen/dws/Files_People/Researchers/gashteovski/oie_nec_labs_gashteovski.pdf). Talk by Kiril Gashteovski given at NEC Labs Europe GmbH, 2019.


## Talks

* [*\[video\] "Open Information Extraction from the Web"*](https://www.youtube.com/watch?v=lMiLiPjGays&feature=youtu.be), by [Prof. Oren Etzioni](https://allenai.org/team/orene/), presented at [AKBC-WEKEX 2012](https://akbcwekex2012.wordpress.com/).


## Code


## Data

OIE output is used as a useful input in many other downstream tasks, such as question answering, event schema induction or generating inference rules. Moreover, OIE output can be used as a "fuel" to derive further resources. Here, the data is organized into two major categories: 1) OIE corpora; 2) Resources derived from OIE output.


### OIE corpora

* [OPIEC: An Open Information Extraction Corpus:](https://www.uni-mannheim.de/dws/research/resources/opiec/) the largest OIE corpus to date, containing more than 341M triples extracted from the entire English Wikipedia. Each triple from the corpus is composed of rich meta-data: each token from the subj / obj / rel along with NLP annotations (POS tag, NER tag, ...), provenance sentence along with the dependency parse, original (golden) left from Wikipedia, sentence order, space / time, etc.
* [\[.gz\] ReVerb extractions](http://reverb.cs.washington.edu/reverb_clueweb_tuples-1.1.txt.gz): 15 million high-precision  OIE extractions (826MB compressed) from the OIE system ReVerb. The extractions were made from the [ClueWeb09 corpus](https://lemurproject.org/clueweb09/). The data contains *(subject, relation, object)* triples, accompanied by a confidence score (estimating the likelihood of whether the triple was correctly  extracted) and provenance information (the link of the web-page where the triple was extracted from).
* [ReVerb extractions (linked)](http://knowitall.cs.washington.edu/linked_extractions/): 3 million triples with linked argument (a subset of the 15 M high-precision ReVerb extractions). The links (to Freebase) are provided by an entity linker. The data fields are: *argument 1, relation phrase, argument 2, freebase ID for argument 1 link, corresponding freebase entity name, link score, link ambiguity score*
* [PATTY](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/patty/): PATTY is a system that takes open relations between two arguments, structures them into relational synsets and then organizes the synsets into a taxonomy. This resource contains over 15M triples with disambiguated arguments (links to WikiPedia articles) and relation synset ID between them. Additionaly, the resource contains: 1) relation pattern synsets with type signatures; 2) relation pattern subsumptions; 3) relation paraphrases; 4) evaluation data;
* [WiseNet (1.0 and 2.0)](http://lcl.uniroma1.it/wisenet/): similarly as PATTY, WiseNet 1.0/2.0 is a source containing of OIE triples, where the arguments are disambiguated and the open relations are organized into relation synsets and then taxonomized. One of the main differences between PATTY and WiseNet is that WiseNet contains "golden links" for the arguments (annotated by humans) by keeping the original links from the WikiPedia articles.
* [KB-Unify](http://lcl.uniroma1.it/kb-unify/): KB-Unify takes as an input several OIE corpora and unifies them into a single disambiguated OIE repository. The open relations are organized into relational synsets and the arguments are disambiguated with BabelFy. 


## Other Repos

- [Awesome-LLM-KG](https://github.com/RManLuo/Awesome-LLM-KG), created by [Linhao Luo](https://rmanluo.github.io) from Monash University.

- [Awesome-Knowledge-Graph-Reasoning](https://github.com/LIANGKE23/Awesome-Knowledge-Graph-Reasoning/tree/main), created by [Ke Liang](https://dblp.org/pid/48/73-6.html) from National University of Defense Technology.

- [oie-resources](https://github.com/gkiril/oie-resources), created by [Kiril Gashteovski](https://www.linkedin.com/in/gashteovski/) from NEC Laboratories Europe.

- [knowledge-graphs](https://github.com/shaoxiongji/knowledge-graphs?tab=readme-ov-file#survey), created by [Shaoxiong Ji](https://www.mv.helsinki.fi/home/shaoxion/) from University of Helsinki.
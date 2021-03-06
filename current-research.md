---
layout: page
title: Current Research Work
---

***

### Hadoop Performanmce Optimization:
The Hadoop MapReduce framework is quite popular in big data analytics. It has various configuration parameters which play an important role in deciding the performance, that is the execution time of a given job. Default values of these parameters do not always result in good performance and hence it is important to tune them. However, tuning the parameters manually is not very easy because of the large and complex nature of the search space. The simultaneous perturbation stochastic approximation (SPSA) algorithm is a noisy gradient algorithm that has been successfully deployed for parameter tuning in a variety of applications ranging from traffic control to service systems. The algorithm tunes the parameters by directly observing the performance of the real system and is independent of parameter dimensions and requires only 2 or fewer observations per iteration. We are working on tuning the parameters using the Simultaneous Perturbation Stochastic Approximation (SPSA) algorithm in order to achieve better performance than the default configuration. 

### Optimizing power and fragmentation in physical memory:
Another research area that our lab works on is to optimize the power consumption by physical RAM in a system. We have been able to off-line up to 80% of free memory which in turn reduces the power consumed by RAM. We are also working on reducing the physical memory fragmentation which facilitates the use of Huge Pages which in turn improves the running time performance of an application. Reducing fragmentation will also help reduce power consumed by the RAM, improve memory hot-plug and also reduce mapping/unmapping cost by using Huge Pages. We have proposed and implemented a new allocator in Linux which gives better performance in terms of power consumption and also in terms of fragmentation.

### Cognitive Modeling of Indian Philosophy:
While modern Science and Technology have significantly expanded our knowledge of nature and the universe around us, and caused significant changes to our material life, a number of fundamental questions have remained un-addressed. For example, "What is the true nature of matter?", "Why and how did life originate?", "Is nature governed by precise laws, is it all random at the lowest levels or is there a superior controlling force?", "How is one to classify something as “right”, “wrong”, “moral”, immoral”? etc. 

It is to philosophy that one must turn, to look for answers to such questions. What do the systems of  philosophy that originated in India (known as darshana-shastras) say about such matters? Indian philosophy contends that the answers to such questions are not always directly accessible or observable and aims to answer the questions in meta-physical terms, concepts, frameworks and rules that are deeply rooted in tarka (logic),  mimamsa (investigation) and vyakarana (grammar). While objectivity, reasoning, inference and investigation are considered important, the questioner is also urged to direct his mind away from the material and mundane and turn it to the spiritual and transcendental. Since the darshana-shastras - a very huge knowledge-base - rely heavily on Ontology (formal naming and definition of the types, properties and interrelationships of fundamental concepts) and Epistemology (rules regarding applicability, validity, limits, scope and nature of knowledge), their underlying structures and axioms (i.e the cognitive model) may be suitably represented in formal logics (eg., Description Logic) and Knowledge representation and reasoning languages (eg., Web Ontology Language - OWL). 

In a collaboration project with PIVS (Paranakusachar Institute of Vedic Studies), we are using a unique and excellent Sanskrit philosophical text called "Mana-Meya-Rahasya-Sloka-Vartikam" for modeling the fundamental philosophical building blocks of Indian philosophy so that one may easily visualize, browse, query and get answers/explanations to philosophical questions as is given by the darshana-shastras as well as get an idea about the vast body of existing literature on Indian philosophy.
              
### Consistency in Distributed systems:
In a distributed system, the data is replicated to provide high availability. These replicas need to be kept consistent and various agreement protocols like 2 Phase Commit, 3 Phase Commit, Group Communication system (GCS) and Paxos are used for this. But each protocol has their own pros and cons depending upon the environment they are being used in. A distributed system might have heterogeneous servers in a heterogeneous network (LAN, WAN, multi-core). It may not be wise to use the same consistency protocol for the entire distributed system. We are designing a hybrid system, where we can insert and remove basic layers as per the application’s requirement and can switch from one protocol to another, or may come up with a new protocol.

### Other Recent areas of work
* Software, Power, Memory Bloat Detection
* Visual search
* Long term archival​
* ​Detection and ​Elimination​ of ​Virtualization overhead ​

***

---
key: RKEM
slug: JavaCallGraphTests
type: conference`
title: "Systematic Evaluation of the Unsoundness of Call Graph Construction Algorithms for Java"
authors:
  - reif
  - kuebler
  - eichberg
  - mezini

published_in: "Proceedings of the 7th ACM SIGPLAN International Workshop on State Of the Art in Program Analysis"
series: SOAP 2018
year: 2018
abstract: >
  Call graphs are at the core of many static analyses ranging from the detection of unused methods to
  advanced control- and data-flow analyses. Therefore, a comprehensive under- standing of the precision
  and recall of the respective graphs is crucial to enable an assessment which call-graph construction
  algorithms are suited in which analysis scenario. For example, malware is often obfuscated and tries
  to hide its intent by using Reflection. Call graphs that do not represent reflective method calls are,
  therefore, of limited use when analyzing such apps.
  
  In general, the precision is well understood, but the recall is not, i.e., in which cases a call graph 
  will not contain any call edges. In this paper, we discuss the design of a compre- hensive test suite that
  enables us to compute a fingerprint of the unsoundness of the respective call-graph construction algorithms.
  This suite also enables us to make a comparative evaluation of static analysis frameworks. Comparing Soot and
  WALA shows that WALA currently has better support for new Java 8 features and also for Java Reflection. However,
  in some cases both fail to include expected edges.
preprint: JCG.pdf
slides: https://www.slideshare.net/MichaelReif1/systematic-evaluation-of-the-unsoundness-of-call-graph-algorithms-for-java
artifact_page: https://bitbucket.org/delors/jcg
---
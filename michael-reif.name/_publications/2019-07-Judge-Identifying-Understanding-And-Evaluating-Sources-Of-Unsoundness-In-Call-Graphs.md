---
key: RKE+
slug: JavaCallGraphTests
type: conference
title: "Judge: Identifying, Understanding, and Evaluating Sources of Unsoundness in Call Graphs"
authors:
  - reif
  - kuebler
  - eichberg
  - helm
  - mezini
published_in: "Proceedings of the 28th ACM SIGSOFT International Symposium  on  Software Testing and Analysis (to appear)"
series: ISSTA
year: 2019
doi: 10.1145/3293882.3330555
abstract: >  
  Call graphs are widely used; in particular for advanced control- and data-flow analyses. Even though many call graph algorithms with different precision and scalability properties have been proposed, a comprehensive understanding of sources of unsoundness, their relevance, and the capabilities of existing call graph algorithms in this respect is missing.
  To address this problem, we propose Judge, a toolchain that helps with understanding sources of unsoundness and improving the soundness of call graphs. In several experiments, we use Judge and an extensive test suite related to sources of unsoundness to (a) compute capability profiles for call graph implementations of Soot, WALA, DOOP, and OPAL, (b) to determine the prevalence of language features and APIs that affect soundness in modern Java Bytecode, (c) to compare the call graphs of Soot, WALA, DOOP, and OPAL – highlighting important differences in their implementations, and (d) to evaluate the necessary effort to achieve project-specific reasonable sound call graphs.

  We show that soundness-relevant features/APIs are frequently used and that support for them differs vastly, up to the point where comparing call graphs computed by the same base algorithms (e.g., RTA) but different frameworks is bogus. We also show that Judge can support users in establishing the soundness of call graphs with reasonable effort.
preprint: RKE+2019_preprint.pdf
artifact_page: https://bitbucket.org/delors/jcg
---
---
key: REHM16
slug: LibCG
type: conference
title: "Call graph construction for Java libraries"
authors:
  - reif
  - eichberg
  - hermann
  - lerch
  - mezini

published_in: "Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations of Software Engineering"
series: FSE 2016
year: 2016
doi: 10.1145/2950290.2950312
abstract: >
  Today, every application uses software libraries. Yet, while a lot of research exists w.r.t. analyzing applications,
  research that targets the analysis of libraries independent of any application is scarce. This is unfortunate, because,
  for developers of libraries, such as the Java Development Kit (JDK), it is crucial to ensure that the library behaves as
  intended regardless of how it is used. To fill this gap, we discuss the construction of call graphs for libraries that
  abstract over all potential library usages. Call graphs are particularly relevant as they are a precursor of many advanced
  analyses, such as inter-procedural data-flow analyses.

  We show that the current practice of using call graph algorithms designed for applications to analyze libraries leads to call
  graphs that, at the same time, lack relevant call edges and contain unnecessary edges. This motivates the need for call graph
  construction algorithms dedicated to libraries. Unlike algorithms for applications, call graph construction algorithms for
  libraries must take into consideration the goals of subsequent analyses. Specifically, we show that it is essential to
  distinguish between the scenario of an analysis for potential exploitable vulnerabilities from the scenario of an analysis for
  general software quality attributes, e.g., dead methods or unused fields. This distinction affects the decision about what
  constitutes the library-private implementation, which therefore, needs special treatment. Thus, building one call graph that
  satisfies all needs is not sensical. Overall, we observed that the proposed call graph algorithms reduce the number of call
  edges up to 30% when compared to existing approaches.
preprint: LibCG.pdf
pages: 474-486
artifact_page: http://www.st.informatik.tu-darmstadt.de/artifacts/dlc/
---


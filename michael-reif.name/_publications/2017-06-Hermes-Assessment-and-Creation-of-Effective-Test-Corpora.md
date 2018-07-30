---
key: REHM17
slug: Hermes
type: workshop
title: "Hermes: assessment and creation of effective test corpora"
authors:
  - reif
  - eichberg
  - hermann
  - mezini

published_in: "Proceedings of the 6th ACM SIGPLAN International Workshop on State Of the Art in Program Analysis"
series: SOAP 2017
year: 2017
doi: 10.1145/3088515.3088523
abstract: >
 An integral part of developing a new analysis is to validate the correctness of its implementation and to demonstrate
 its usefulness when applied to real-world code. As a foundation for addressing both challenges developers typically use
 custom or well-established collections of Java projects. The hope is that the collected projects are representative for
 the analysis’ target domain and therefore ensure a sound evaluation. But, without proper means to understand how and to
 which degree the features relevant to an analysis are found in the projects, the evaluation necessarily remains inconclusive.
 Additionally, it is likely that the collection contains many projects which are – w.r.t. the developed analysis – basically
 identical and therefore do not help the overall evaluation/testing of the analysis, but still cost evaluation time. To overcome
 these limitations we propose Hermes, a framework that enables the systematic assessment of given corpora and the creation of
 new corpora of Java projects. To show the usefulness of Hermes, we used it to comprehend the nature of the projects belonging to
 the Qualitas Corpus (QC) and then used it to compute a minimal subset of all QC projects useful for generic data- and
 control-flow analyses. This subset enables effective and efficient integration test suites.
preprint: Hermes.pdf
pages: 43-48
website: http://www.opal-project.de/Hermes.html
---


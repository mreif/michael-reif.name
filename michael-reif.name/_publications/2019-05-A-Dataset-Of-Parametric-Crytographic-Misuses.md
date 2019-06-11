---
key: WRE+
slug: CryptoMisuses
type: conference
title: "A Dataset of Parametric Cryptographic Misuses"
authors:
  - wickert
  - reif
  - eichberg
  - dodhy
  - mezini
published_in: "2019 IEEE/ACM 16th International Conference on Mining Software Repositories"
series: MSR
year: 2019
abstract: >  
  Cryptographic APIs (Crypto APIs) provide the foundations for the development of secure applications. Unfortunately, most applications do not use Crypto APIs securely and end up being insecure, e.g., by the usage of an outdated algorithm, a constant initialization vector, or an inappropriate hashing algorithm. Two different studies have recently shown that 88% to 95% of those applications using Crypto APIs are insecure due to misuses. To facilitate further research on these kinds of misuses, we created a collection of 201 misuses found in real-world applications along with a classification of those misuses. In the provided dataset, each misuse consists of the corresponding open-source project, the project’s build information, a description of the misuse, and the misuse’s location. Further, we integrated our dataset into MUBench , a benchmark for API misuse detection. Our dataset provides a foundation for research on Crypto API misuses. For example, it can be used to evaluate the precision and recall of detection tools, as a foundation for studies related to Crypto API misuses, or as a training set.
preprint: WRE+2019.pdf
artifact_page: 
---
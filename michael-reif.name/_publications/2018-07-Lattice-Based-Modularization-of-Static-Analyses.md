---
key: EKHR+
slug: Fix-point Compuation Framework
type: conference
title: "Lattice Based Modularization of Static Analyses"
authors:
  - eichberg
  - kuebler
  - helm
  - reif
  - salvaneschi
  - mezini
published_in: "Proceeding ISSTA '18 Companion Proceedings for the ISSTA/ECOOP 2018 Workshops"
series: SOAP 2018
year: 2018
pages: 113-118
doi: 10.1145/3236454.3236509
abstract: >
  Static analyses which compute conceptually independent information, e.g., class immutability or method purity are typically developed as standalone, closed analyses. Complemen- tary information that could improve the analyses is either ignored by making a sound over-approximation or it is also computed by the analyses but at a rudimentary level. For ex- ample, an immutability analysis requires field mutability in- formation, alias/escape information, and information about the concurrent behavior of methods to correctly classify classes like java.lang.String or java.util.BigDecimal. As a result, without properly supporting the integration of in- dependently developed, mutually benefiting analysis, many analyses will not correctly classify relevant entities.

  We propose to use explicitly reified lattices that encode the information about a source code element’s properties (e.g., a method’s purity or a class’ immutability) as the sole interface between mutually dependent analyses. This en- ables the composition of multiple analyses. Our case study shows that using such an approach enables highly scalable, lightweight implementations of modularized static analyses.
preprint: FPCF.pdf
---
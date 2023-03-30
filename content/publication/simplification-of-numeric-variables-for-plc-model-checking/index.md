---
title: Simplification of numeric variables for PLC model checking
publication_types:
  - "0"
authors:
  - admin
doi: 10.1145/3487212.3487334
abstract: "Software model checking has recently started to be applied in the
  verification of programmable logic controller (PLC) programs. It works
  efficiently when the number of input variables is limited, their interaction
  is small and, thus, the number of states the program can reach is not large.
  As observed in the large code base of the CERN industrial PLC applications,
  this is usually not the case: it thus leads to the well-known state-space
  explosion problem, making it impossible to perform model checking. One of the
  main reasons that causes state-space explosion is the inclusion of numeric
  variables due to the wide range of values they can take. In this paper, we
  propose an approach to discretize PLC input numeric variables (modelled as
  non-deterministic). This discretization is complemented with a set of
  transformations on the control-flow automaton that models the PLC program so
  that no extra behaviours are added. This approach is then quantitatively
  evaluated with a set of empirical tests using the PLC model checking framework
  PLCverif and three different state-of-the-art model checkers (CBMC, nuXmv, and
  Theta), showing beneficial results for binary-decision-diagram-based model
  checkers."
draft: false
featured: false
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2021-11-22T22:24:57.524Z
---

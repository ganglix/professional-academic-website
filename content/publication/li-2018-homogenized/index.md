---
title: 'Homogenized-model-simplified-circuit: code for the simplified circuit model'
authors:
- Gang Li
- Richard Evitts
- Moh Boulfiza
date: '2018-08-01'
publishDate: '2024-01-01T06:45:30.891911Z'
publication_types:
- article-journal
publication: '*Zenodo*'
doi: 10.5281/ZENODO.1406210
abstract: The model is firstly solved at the “open circuit mode” to find the OCP.
  In “scan mode”, the scan starts from the OCP, and increases/ decreases at a small
  increment (e.g. 0.5 mV) to alter the homogenized area-averaged rebar electrode potential,
  until it reaches to a given scan range bounds (e.g. OCP-300 mV or OCP+ 300 mV).
  The simulated potentiodynamic scan procedure was coded up in Python; the group of
  equations in both “open circuit model” and “scan mode” were numerically solved with
  iterative optimization algorithm from Scipy in Python ecosystem. To optimize the
  convergence during solving, solutions from the previous scan step were used as initial
  guesses for the next scan step.
links:
- name: URL
  url: https://doi.org/10.5281/zenodo.1406210#.XOWMSJ5IzUc.mendeley
---
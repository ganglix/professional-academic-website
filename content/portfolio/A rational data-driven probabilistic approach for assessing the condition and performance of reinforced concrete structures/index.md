---
title: A rational data-driven probabilistic approach for assessing the condition and performance of reinforced concrete structures
summary: "This research project developed software using probabilistic life-cycle deterioration models for RC structures. It assesses current conditions and predicts future performance using field data, enabling effective scheduling of maintenance or repairs to extend the asset's life. The software evaluates various deterioration stages, enhancing asset management."
tags:
  - Bridge
  - Concrete
  - Chloride
  - Carbonation
  - Corrosion
  - Service life
  - Life cycle
  - Software
date: "2021-03-30T00:00:00Z"

links:
  - icon: 
    icon_pack:
    name: software
    url: '../../publication/li-2022-rationalrc/'

show_related: true
---
## **Background Information**

One significant challenge facing the world today is the decay of infrastructure and how this deterioration is perceived to affect serviceability.  With most government agencies stretched for funding, infrastructure serviceability will decline unless significant funds are made available to replace the apparent deficient structures.  However, if improvements are made in the prediction of existing conditions and the performance and effectiveness of rehabilitation and maintenance strategies, existing budgets may be sufficient to maintain our current serviceability by providing maintenance and repair strategies targeted at maintaining or improving serviceability that are based on the effect each deterioration process has on the performance of the structure.  

Unfortunately, most methods for estimating service life or repair benefit are based on judgmental methods borne of experience, which often produce a highly conservative estimate of service life which results in structures being replaced before it is necessary.  These types of approaches must be replaced as infrastructure providers cannot remain a “low technology” industry, relying on tacit or implicit prediction and management methods.

One of the major components of modern infrastructure decay is due to the corrosion of embedded reinforcing steel in reinforced concrete (RC) structures. Prediction and early diagnosis of corrosion have become a very important task for engineers, repair practitioners, and owners of buildings and bridges as it allows preventive action to take place and avoids unnecessary repairs, and hence, leads to a reduced life cycle cost. Additionally, it helps policymakers with regulating the evaluation criteria to choose optimal rehabilitation strategies for RC structures that may have exceeded their design lives but that do not necessarily need to be replaced. 

Unfortunately, current asset management practice is often based on historical data and the design service life, and hence, it lacks the capability to assess the current condition of an RC structure to select an optimal course of action. Often, structures are torn down just because the original service life has been exceeded, which produces unnecessary costs to society and generates tremendous waste and environmental impact. Furthermore, maintenance schedules are usually based on pre-set actions with little input from the actual current condition of the structure. 

Without adequate assessment, the rehabilitation strategies involve a lot of “guesswork,” which results in suboptimal rehab or repair strategies that have limited to no benefit to the structure. With reliable condition assessment methods and robust prediction probabilistic models, rational timely maintenance schedules can be developed, and the remaining service life can be dynamically adjusted based on the rehabilitation measures that have been actually implemented.

## **Research outcomes**

The research results of this study were implemented in a software package that incorporates probabilistic life-cycle deterioration models. This package is able to use site-specific test data, such as concrete cover reading, half-cell mapping, chloride profiling, moisture content etc. to provide a probabilistic prediction of the RC structure’s condition at each deterioration stage: membrane failure, chloride or carbonation penetration, corrosion with rebar section loss, and concrete cover cracking.

## **methods and techniques**

### Probabilistic approach

The limit-state probabilistic approach was used throughout the model framework. The probabilistic approach concept of “load” and “resistance” used in the area of structural reliability is extended to different deterioration mechanisms shown in the cover figure. The probability of failure is defined as the probability when “load” exceeds the “resistance”.

### Modularized deterioration mechanism

The practical implementation of the complete model was broken into four modules, with each module coping with a specific deterioration stage. The calculated probability of failure propagates into the next stage. The individual modules were coded using an object-oriented program featuring probabilistic variables to provide predictions with uncertainties. The software structure allows each module to be self-contained and upgradable in the future. 

### Different modelling techniques
Different modelling techniques were used to tackle different deterioration mechanisms

•	membrane: 
a statistical model
•	chloride: 
a modified Fick’s second law considering advection zone
•	carbonation: 
a modified empirical square-root-of-time model considering material properties and environment factors

•	corrosion: 
a regressed analytical solution from a 2-D electrochemical numerical model 
	a pore-scaled corrosion model developed considering the synergetic effect of the water saturation, pH and chloride content.

•	cracking:
a thick-walled cylinder model

Laboratory Tests
Electrochemical tests were carried out to study the interactive effects of chloride-pH-moisture on rebar corrosion and rust formation. The pre-passivated carbon steel rebars were cast in mortar samples with six levels of chloride content and two levels of carbonation. The samples were conditioned at various humidity levels (RH 60%, 80%, 95% and submerged). The corrosion parameters (corrosion potential, corrosion current density) were tested in non-submerged conditions with an improved potentiodynamic scan. The results help improve the current corrosion model with the added synergetic effect of chloride-pH-moisture.

Field data acquisition 
In addition to the routine survey data, the in-house developed time-domain reflectometry (TDR) moisture sensors were used to collect the liquid water content in the concrete cover. 

## Related publication

Software

[Rational-RC: A Practical Life Cycle Deterioration Modelling Framework for Reinforced Concrete Structures](../../publication/li-2022-rationalrc/)

Paper

[On the corrosion parameters acquired through potentiodynamic scans of carbon steel rebar in simulated pore solution and mortar](../../publication/li-2023-corrosion/)
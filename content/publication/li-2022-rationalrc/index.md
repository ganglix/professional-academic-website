---
title: 'Rational-RC: A Practical Life Cycle Deterioration Modelling Framework for Reinforced Concrete Structures'
authors:
- Admin
- Jim Zacaruk
- Moh Boulfiza
date: '2023-07-01'
publishDate: '2024-01-01T20:46:05.092317Z'
publication_types:
- software
publication: '*Open Source Software*'
version: v0.2.3

summary: Rational-RC is a practical life cycle deterioration modelling framework. It utilizes the field survey data and provides probabilistic predictions of the RC structure deterioration through different stages of the service life cycle. It covers various deterioration mechanisms such as membrane deterioration, concrete carbonation and chloride penetration, corrosion and cracking.

links:
- name: Documentation URL
  url: https://magical-sherbet-9ac2a8.netlify.app/
- name: Tutorial
  url: https://magical-sherbet-9ac2a8.netlify.app/tutorials/tutorial_index
tags:
- Reinforced Concrete
- Deterioration Modelling
- Civil Engineering
- Structural Analysis
- Software
# Display this page in the Featured widget?
featured: true

show_related: true

---
# Rehab bridge with confidence

## About Rational-RC
Rational-RC is a practical life cycle deterioration modelling framework. It utilizes the field survey data and provides probabilistic predictions of the RC structure deterioration through different stages of the service life cycle. It covers various deterioration mechanisms such as membrane deterioration, concrete carbonation and chloride penetration, corrosion and cracking.

## Full Service Life Cycle

One of the major components of modern infrastructure decay is due to the corrosion of embedded reinforcing steel in reinforced concrete (RC) structures. Prediction and early diagnosis of corrosion have become a very important task for engineers, repair practitioners, and owners of buildings and bridges. Traditional approach for estimating service life or repair benefit are based on judgmental methods borne of experience, which often produce a highly conservative estimate of service life which results in structures being replaced before it is necessary.  
![life cycle image](life_cycle.png "Life-cycle deterioration")

Life cycle cost is reduced by taking preventive actions and avoiding unnecessary repairs. Additionally, it helps policymakers with regulating the evaluation criteria to choose optimal rehabilitation strategies for RC structures that may have exceeded their design lives but that do not necessarily need to be replaced. 
![Probability cost image](probability_cost.png "Probability of damage and associated costs")

## Probabilistic Prediction with Confidence

### The limit-state probabilistic approach
The probabilistic approach concept of “load” and “resistance” used in the area of structural reliability is extended to different deterioration mechanisms. The probability of failure is defined as the probability when “load” exceeds the “resistance”.
![limit state image](probablistic_approach.png "Limit states")

### Modularized deterioration mechanism
The practical implementation of the complete model was broken into self-contained modules, with each module coping with a specific deterioration stage. The calculated probability of failure propagates into the next stage. 

## Integrated workflow
![flow chart](Rational_RC_flow_chart.png "Work flow")
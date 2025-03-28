---
title: A rational data-driven probabilistic approach for assessing the condition and performance of reinforced concrete structures  
summary: This project delivers a modular, software-based solution for probabilistic life-cycle deterioration modelling of RC structures. It enables asset owners to assess current condition and predict future performance using field data, optimizing maintenance schedules and extending service life.  
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

## **Project Overview**

The deterioration of reinforced concrete (RC) infrastructure due to corrosion and environmental exposure poses a substantial challenge for asset management. This project responds to that challenge through the development of **Rational-RC**, a Python-based software platform that integrates probabilistic life-cycle modelling with field-based diagnostics.

The tool allows engineers and asset owners to evaluate current structure condition, simulate future deterioration, and make data-driven decisions on repair timing and strategy selection. It supports performance-based planning over the entire life cycle of RC structures.

## **Engineering Contributions**

- **Limit-State Probabilistic Framework:**  
The software extends the structural reliability concepts of “load” and “resistance” to model various deterioration mechanisms. Failure probability is computed when deterioration demand exceeds material resistance.

- **Modular Mechanism-Based Design:**  
Deterioration processes are modularized into five stages: membrane degradation, chloride ingress, carbonation, corrosion initiation and propagation, and cracking. Each module operates independently with upgradable code architecture.

- **Mechanistic Models Used:**
  - **Membrane:** Statistical performance-based model  
  - **Chloride:** Modified Fick’s law accounting for advection  
  - **Carbonation:** Empirical square-root-of-time model  
  - **Corrosion:** Regressed 2D electrochemical model and a pore-scale mechanistic model incorporating chloride, pH, and moisture  
  - **Cracking:** Thick-walled cylinder stress model  

## **Laboratory and Field Integration**

- **Electrochemical Testing:**  
Experimental work investigated the combined influence of chloride content, pH, and moisture on steel corrosion. Mortar samples embedded with carbon steel rebars were tested under multiple conditioning environments (RH 60%–100%) to support model calibration.

- **Custom Sensor Deployment:**  
A proprietary time-domain reflectometry (TDR) sensor was used to monitor in-situ moisture in concrete cover layers, enhancing the reliability of deterioration predictions.

## **Software Capabilities**

- Utilizes real-world data such as cover depth, chloride profiles, and half-cell potentials  
- Predicts condition across deterioration stages  
- Supports rational intervention scheduling and life-extension planning  

## **Related Publications**

- [Rational-RC: A Practical Life Cycle Deterioration Modelling Framework for Reinforced Concrete Structures](../../publication/li-2022-rationalrc/)  
- [On the Corrosion Parameters Acquired Through Potentiodynamic Scans of Carbon Steel Rebar in Simulated Pore Solution and Mortar](../../publication/li-2023-corrosion/)

---
title: Potentiodynamic polarization fitter
summary: "Interactive Streamlit app for fitting Butler-Volmer and BV + film models to potentiodynamic polarization data. Supports Gamry .DTA files, signed .csv/.xlsx data, and one-step or two-step absolute-current Excel inputs, with LPR cross-checks and post-hoc IR compensation."
show_date: false
image:
  caption: ''
  preview_only: true
  focal_point: Smart

links:
  - icon:
    icon_pack:
    name: source code
    url: 'https://github.com/ganglix/potentiodynamic-polarization-handler'

  - icon:
    icon_pack:
    name: external link
    url: 'https://potentiodynamic-polarization-fitter.streamlit.app'

tags:
- potentiodynamic scan
- tafel
- fitting
- gamry
- software
---
If the webapp is not displaying correctly in your browser, use the [**external link**](https://potentiodynamic-polarization-fitter.streamlit.app) or open it in full screen.

This Streamlit app fits potentiodynamic polarization data using Butler-Volmer and BV + film growth/dissolution models. It supports Gamry `.DTA` files, signed current `.csv` and `.xlsx` files, and one-step or two-step absolute-current Excel formats.

The app reports key corrosion parameters including `Ecorr`, `Icorr`, current density, anodic and cathodic Tafel slopes, Stern-Geary `B`, polarization resistance `Rp`, goodness-of-fit metrics, and an LPR cross-check.

<iframe
  src="https://potentiodynamic-polarization-fitter.streamlit.app/?embed=true"
  height="1000"
  width="100%"
  style="border: none;"
></iframe>

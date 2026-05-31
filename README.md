# carotid-hemodynamic-analysis
CFD simulation and physical flow visualization of carotid artery hemodynamics under varying exercise conditions

# Carotid Artery Hemodynamic Analysis
**University of Arizona | 2025**

## Overview
A dual-method study combining computational fluid dynamics (CFD) simulation 
and physical flow visualization to investigate blood flow patterns and wall 
shear stress in the carotid artery under rest, moderate exercise, and intense 
exercise conditions. Findings have implications for understanding 
atherosclerosis risk and vascular health.

## My Contributions
- Configured and ran CFD simulations in ANSYS Fluent applying steady-state 
  Navier-Stokes equations across three Reynolds number conditions (Re = 474, 711, 947)
- Preprocessed and repaired anatomical STL mesh in Meshmixer — remeshing, 
  patching geometry defects, and scaling to experimental dimensions
- 3D printed hollow carotid bifurcation model in clear PLA on Ultimaker S3
- Designed and operated a flow visualization apparatus using fluorescent dye 
  injection under blacklight illumination
- Analyzed recorded footage frame-by-frame in ImageJ to quantify flow 
  velocity and flow separation regions
- Correlated experimental and computational results to validate findings

## System Architecture
- **Computational:** ANSYS Fluent CFD with Navier-Stokes steady-state solver, 
  boundary conditions modeling physiological inlet velocity, zero-pressure 
  outlets, and no-slip wall constraints
- **Physical:** 3D printed carotid model, flow tank, fluorescent dye injection, 
  blacklight illumination, ImageJ video analysis
- **Mesh:** Anatomical STL from Thingiverse, repaired and scaled in Meshmixer, 
  element size 0.0001 m with adaptive sizing level 4

## Key Results
- Validated laminar flow maintenance across all three exercise conditions
- Identified low wall shear stress (WSS) regions in the carotid sinus 
  associated with elevated atherosclerosis risk
- Confirmed helical flow pattern at bifurcation apex across all conditions
- Correlated experimental Reynolds numbers (125–158) with computational 
  predictions (474–947) to characterize scaling behavior

## Tools & Technologies
ANSYS Fluent · Meshmixer · ImageJ · SolidWorks · Ultimaker S3 · 
Navier-Stokes CFD · Flow visualization · Python

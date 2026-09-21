---
title: "Data-driven material model calibration for high-velocity impact using ensemble-based data assimilation"
collection: talks
type: "Talk"
permalink: /talks/2026-06-22-Data-driven-material-model-calibration-for-high-velocity-impact-using-ensemble-based-data-assimilation
venue: "20th U.S. National Congress on Theoretical and Applied Mechanics"
date: 2026-06-22
location: "Pasadena, California, USA"
---

High-fidelity high-velocity impact (HVI) simulations rely on accurate material models, yet traditional manual parameter calibration is labor-intensive and requires extensive experimentation. This study develops an ensemble-based data assimilation (DA) framework to automatically and simultaneously calibrate plasticity, fracture, and equation of state (EOS) parameters using data from a single HVI test. The framework integrates Smoothed Particle Hydrodynamics (SPH) for HVI simulation, the ensemble Kalman filter (EnKF) for parameter refinement, and adaptive covariance inflation to mitigate uncertainty underestimation.
The approach is demonstrated using synthetic back-face deflection data of an AZ31B magnesium plate to identify parameters in the Johnson-Cook and Mie-Grüneisen models. We evaluated the framework under various conditions, including biased initial guesses and limited observational data. Results show that EnKF accurately recovers sensitive material parameters within five iterations, characterized by a convergent ensemble standard deviation. Conversely, insensitive parameters exhibit persistent uncertainty, positioning the ensemble standard deviation as a valuable diagnostic tool for assessing calibration reliability.
Further analysis indicates that while limited data may increase the required iterations, convergence remains achievable. Under extreme prior bias, sensitive parameters exhibit a "drift-then-stall" behavior, where posterior spreads shrink and errors decrease despite small residual biases. This research demonstrates the robustness and efficiency of the proposed DA framework for autonomous material characterization in HVI problems, offering a significant improvement over traditional fitting methods.

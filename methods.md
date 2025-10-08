---
layout: page
title: "Methods"
permalink: /research/methods
---

## Climate data

IcyAlert will use climate datasets from [CMIP6](https://doi.org/10.5194/gmd-9-1937-2016) (~1° resolution) and the upcoming CMIP7 to analyze large-scale Arctic climate variability. A single-model initial-condition large ensemble ([SMILE](https://doi.org/10.5194/gmd-18-6341-2025)) will also be employed to extend training data from CMIP6/CMIP7 and enhance probabilistic predictions. IcyAlert will integrate winter conditions from the Copernicus Climate Change Service (C3S) multi-model seasonal forecasting system to improve next-year Arctic predictions. Model performance will be validated against satellite and reanalysis data.

## Causal analysis

IcyAlert will use the [Liang-Kleeman information flow (LKIF)](https://doi.org/10.3390/e23060679) method as a primary causal method to quantify causal interactions between the different climate variables. This causal method will allow us to go beyond classical correlation analyses and identify the predictors of ice-free Arctic conditions, as well as its climate impacts. In IcyAlert, we will combine LKIF with explainable AI to improve ice-free Arctic predictions and assess its regional climate impacts. To ensure robustness, we will also compare results against alternative causal methods.

## AI-powered climate emulators

IcyAlert will develop a probabilistic ice-free Arctic predictor that maps inputs from integrated preconditions and drivers to outputs of summer sea-ice metrics and climate impact indices. Using
advanced probabilistic techniques such as Graph Neural Networks (e.g. [GraphCast](https://doi.org/10.1126/science.adi2336)) and diffusion models (e.g. [GenCast](https://doi.org/10.1038/s41586-024-08252-9)), the model will generate risk-informed predictions of ice-free conditions. This will form a prototype ice-free emulator, simulating ice-free scenarios under varying initial conditions and providing probabilistic outputs for decision-making and scenario analysis.

## Gefion

IcyAlert will use the [Gefion supercomputer](https://novonordiskfonden.dk/en/news/denmarks-first-ai-supercomputer-is-now-operational/) to perform its computations.

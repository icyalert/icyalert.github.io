---
layout: page
title: "Research"
permalink: /research
---

## 1. Context

Arctic summer sea ice has been declining at an unprecedented rate, mainly caused by anthropogenic global warming ([IPCC, 2021](https://doi.org/10.1017/9781009157896.001)). The visible transition from ice-covered (high albedo) to ice-free (low albedo) ocean in summer amplifies solar heat absorption, intensifying surface warming ([Stroeve & Notz, 2018](https://doi.org/10.1088/1748-9326/aade56)). This positive feedback accelerates polar amplification, drives further sea ice loss, and triggers cascading impacts on the global climate ([Meier & Stroeve, 2022](https://doi.org/10.5670/oceanog.2022.114)). Since 1979, the Arctic has warmed nearly four times faster than the global average ([Rantanen et al., 2022](https://doi.org/10.1038/s43247-022-00498-3)).

While the Intergovernmental Panel on Climate Change (IPCC) projects a summer ice-free Arctic (sea-ice area below 1 million km²) by mid-century ([IPCC, 2021](https://doi.org/10.1017/9781009157896.011)), emerging research highlights significant uncertainties, suggesting that the first ice-free day could occur as early as 2030, with timing projections varying widely across models and scenarios ([Jahn et al., 2024](https://doi.org/10.1038/s43017-023-00515-9)). Moreover, the loss of summer sea ice undermines climate stability at high and mid-latitudes, potentially fueling extreme weather and causing regional impacts, even if large uncertainties remain (e.g. [Outten et al., 2023](https://doi.org/10.5194/wcd-4-95-2023)).

In IcyAlert, we propose to address these uncertainties and to refine predictions of ice-free Arctic summers based on global climate models and satellite observations combined with causal analysis and explainable artificial intelligence (AI). This approach will not only improve the prediction accuracy of ice-free Arctic summers but will also provide deeper insights into the drivers of Arctic sea-ice variability, enabling more reliable early warning systems for regional climate impacts.

&ensp;

## 2. Objectives

In IcyAlert, we propose to develop an **early warning system** for summer ice-free Arctic predictions (sea-ice area below 1 million km²) and its climate impacts. 

The three key project objectives of IcyAlert are:

**Objective 1**: Build a **prototype IcyAlert system** with bias correction and precondition detection using integrated observations and **CMIP6** data. We aim to derive the dynamical driving ice-free conditions in the Arctic, providing a baseline method for future model evaluation.

**Objective 2**: Optimize IcyAlert with **AI-driven ensemble simulations** and **causal analysis** for prioritized key climate processes. We aim to refine predictions and uncover key Arctic sea-ice impacts.

**Objective 3**: Apply IcyAlert to **CMIP7** data for downscaled year-round climate impact simulations and deliver **risk alerts** for the Arctic and extratropics. By leveraging a hierarchy of models, from AI/ML-enhanced predictions to downscaled impact models, we aim to use causal networks to enable localized risk assessments and actionable insights into abrupt climate changes and extreme events.

&ensp;

## 3. Methods

### Climate data

IcyAlert will use climate datasets from [CMIP6](https://doi.org/10.5194/gmd-9-1937-2016) (~1° resolution) and the upcoming CMIP7 to analyze large-scale Arctic climate variability. A single-model initial-condition large ensemble ([SMILE](https://doi.org/10.5194/gmd-18-6341-2025)) will also be employed to extend training data from CMIP6/CMIP7 and enhance probabilistic predictions. IcyAlert will integrate winter conditions from the Copernicus Climate Change Service (C3S) multi-model seasonal forecasting system to improve next-year Arctic predictions. Model performance will be validated against satellite and reanalysis data.

### Causal analysis

IcyAlert will use the [Liang-Kleeman information flow (LKIF)](https://doi.org/10.3390/e23060679) method as a primary causal method to quantify causal interactions between the different climate variables. This causal method will allow us to go beyond classical correlation analyses and identify the predictors of ice-free Arctic conditions, as well as its climate impacts. In IcyAlert, we will combine LKIF with explainable AI to improve ice-free Arctic predictions and assess its regional climate impacts. To ensure robustness, we will also compare results against alternative causal methods.

### AI-powered climate emulators

IcyAlert will develop a probabilistic ice-free Arctic predictor that maps inputs from integrated preconditions and drivers to outputs of summer sea-ice metrics and climate impact indices. Using
advanced probabilistic techniques such as Graph Neural Networks (e.g. [GraphCast](https://doi.org/10.1126/science.adi2336)) and diffusion models (e.g. [GenCast](https://doi.org/10.1038/s41586-024-08252-9)), the model will generate risk-informed predictions of ice-free conditions. This will form a prototype ice-free emulator, simulating ice-free scenarios under varying initial conditions and providing probabilistic outputs for decision-making and scenario analysis.

### Gefion

IcyAlert will use the [Gefion supercomputer](https://novonordiskfonden.dk/en/news/denmarks-first-ai-supercomputer-is-now-operational/) to perform its computations.

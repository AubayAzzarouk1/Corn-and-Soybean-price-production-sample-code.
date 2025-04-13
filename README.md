Multimodal Spatio-Temporal Vision Transformer (MMST-ViT) for Agricultural Yield Prediction

Project Overview

This repository contains code and implementation details for our innovative machine learning approach aimed at enhancing climate awareness and agricultural decision-making. Our primary focus is predicting corn and soybean yields by leveraging climate data, satellite imagery, and historical yield information.

Motivation

Agricultural productivity is significantly influenced by climate variability and change. Accurate yield predictions help policymakers and farmers make informed decisions. Traditional regression models lack the complexity needed to interpret multimodal data effectively, prompting the development of our novel MMST-ViT model.

Features

Integration of satellite imagery from the CropNet database.

Custom data preprocessing pipelines for synchronizing multimodal inputs.

Advanced Vision Transformer architecture (MMST-ViT) optimized for spatial-temporal data.

Implementation Highlights

Developed tailored data loaders and preprocessing routines.

Iteratively debugged model to handle GPU memory constraints and ensure stable convergence.

Tuned hyperparameters (transformer layers, embedding dimensions, attention heads) to maximize predictive accuracy.

Data Sources

USDA yield historical time series.

CropNet satellite imagery database.

Climate data (temperature, precipitation, soil moisture).


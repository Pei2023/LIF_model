# Leaky Integrate-and-Fire (LIF) Model

This repository contains a Jupyter Notebook implementing a single-neuron
Leaky Integrate-and-Fire (LIF) model as part of my self-study in
computational neuroscience.

## Source

This implementation follows a publicly available tutorial:
https://compneuro.neuromatch.io/tutorials/W2D3_BiologicalNeuronModels/student/W2D3_Tutorial1.html

The code was rewritten step by step to understand the mathematical formulation
and numerical simulation of the LIF model.

## Current status

- Implemented numerical simulation of a single LIF neuron
- Analyzed subthreshold membrane potential dynamics

## Planned extensions

- Response of the LIF model to different types of input currents:
  - Constant (DC) input
  - Noisy input currents
- Investigation of how different input current regimes lead to
  subthreshold dynamics or spike generation in the LIF model

## Files

- `LIF.ipynb`: numerical simulation and analysis of the LIF neuron

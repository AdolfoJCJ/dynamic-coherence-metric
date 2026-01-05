# Dynamic Conversational Coherence Metric

This repository contains the reference implementation of a minimal dynamic metric for
conversational coherence, defined as a time-indexed signal C(t) that tracks alignment
between conversational turns and an evolving contextual representation.

The implementation accompanies the paper:

Adolfo J. Céspedes Jiménez (2026)  
*A Minimal Metric for Dynamic Conversational Coherence*

## Overview
Conversational coherence is modeled here as a continuous, turn-by-turn signal rather than
as a static or aggregate property. The metric is intentionally minimal and model-agnostic:
it does not assume speaker intention, pragmatic inference, or psychological state, and can
be implemented using different semantic representations and similarity functions.

This repository provides a fully reproducible Google Colab notebook illustrating the core
metric, example data, and representative figures.

## Repository contents
- `notebook/`  
  Reference Jupyter notebook implementing the dynamic coherence metric.

- `data/`  
  Small example dialogue dataset used for demonstration and reproduction.

- `requirements.txt`  
  Python dependencies required to run the notebook.

## How to run
1. Open the notebook in Google Colab or a local Jupyter environment.
2. Install the dependencies listed in `requirements.txt` if running locally.
3. Run all cells sequentially from top to bottom.

The notebook is self-contained and produces all figures reported in the example.

## Reproducibility
The code and data provided here are intended for methodological illustration and
reproducibility. The example dataset is synthetic and does not contain sensitive or
personal information.

## License
This project is released under the MIT License.

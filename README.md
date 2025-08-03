# GPU Model Serving Lab

Local deployment of ML models on GPU using K3s, Triton, and KServe:
- fast and reproducible setup and use
- gradual extension to production-like workflows

## Structure

- notebooks/: step-by-step reproducible notebooks
- models/: model artifacts, organized by format/backend/version
- deployments/: kubernetes manifests, inference request scripts
- scripts/: helpers for model conversion, payload generation

## Prerequisites

- Python 3.12
- conda
- NVIDIA GPU

## Quickstart

Run notebooks one by one
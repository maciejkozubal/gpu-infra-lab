# GPU Model Serving Lab

Local deployment of ML models on GPU using K3s, Triton, and KServe:
- fast setup
- reproducible inference
- gradual extension to production-like workflows

## Structure

- `notebooks/`: step-by-step reproducible notebooks
- `models/`: model artifacts, organized by format/backend/version
- `deployments/`: kubernetes manifests, inference request scripts
- `scripts/`: helpers for model conversion, payload generation<!--, benchmarking -->
<!-- - `outputs/`: logs, metrics, screenshots, inference results -->


## Prerequisites

- Python 3.12 
- [conda](https://docs.conda.io/en/latest/miniconda.html)

## Quickstart

Run notebooks one by one
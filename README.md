# Dataset Usage and Creation in Cybersecurity Research

This repository contains artifacts for reproducing the analyses in our paper.

## Contents

- `data/processed/`: processed datasets and manually verified annotations
- `prompts/`: prompts used in the LLM-assisted extraction pipeline
- `scripts/`: normalization, analysis, statistics, and visualization scripts
- `results/`: generated tables and figures
- `figures/`: figure/tables outputs used in the paper

## Key Files

- `manual_baseline.csv`: dataset-level records used in the analysis
- `creation_motivations.csv`: motivation labels for created datasets
- `domain_paper_level.csv`: research domain and subdomain labels paper level
- `domain_instances.csv`: research domain and subdomain instances per paper
- `LLMgpt_vs_final_baseline_field_judgments.csv`: LLM output compared against manual annotations

## Reproducing Results

Install dependencies:

```bash
pip install -r requirements.txt

# PQC Attack Surface — [Team Name]
Short description: Code and experiments for "Examining the Attack Surface of PQC".

# 🎯 Project Goal

Study and demonstrate the attack surface of Post-Quantum Cryptography (PQC) by:

Building small, toy implementations to learn internal data flows.
Running reproducible algorithmic and implementation experiments (e.g., brute-force, simulated side-channel).
Showing how parameter choices and coding mistakes can reduce security.

## Repo layout — what each part is for
/README.md                 # high-level project overview (see template below)
/docs/                     # literature notes, protocols, SOPs, ethics doc
/src/                      # code: examples, toy_kem, analysis scripts
/experiments/              # experiment code and notebooks by experiment id
/experiments/BF-001/       # example: bruteforce toy experiment
/data/                     # raw data, traces (NOT committed if large)
/notebooks/                 # exploratory Jupyter notebooks
/docker/                   # Dockerfile + scripts for reproducibility
/.github/                  # GitHub workflows, issue/PR templates
/tests/                    # automated tests (basic smoke tests)
requirements.txt
Dockerfile
README.md
CONTRIBUTING.md
CODE_OF_CONDUCT.md
LICENSE




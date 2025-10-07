# PQC Attack Surface — [Team Name]
Short description: Code and experiments for "Examining the Attack Surface of PQC".

# 🎯 Project Goal

Study and demonstrate the attack surface of Post-Quantum Cryptography (PQC) by:

Trying small, toy implementations to learn internal data flows.
Running reproducible algorithmic and implementation experiments (e.g., brute-force, simulated side-channel).
Showing how parameter choices and coding mistakes can reduce security.

## 🗂️ Repository Layout
```bash
README.md                 → High-level project overview
requirements.txt          → Python dependencies
src/                      → Toy KEM + Kyber example (code)
  ├─ toy_kem.py
  └─ kyber_example.py
experiments/              → Experiment scripts and results
  └─ bruteforce/
      └─ run_bruteforce.py
docs/                     → Literature notes, ethics, SOPs
data/                     → Raw data or traces (not committed if large)
notebooks/                → Jupyter notebooks for analysis
.github/                  → Workflow & issue templates
docker/                   → Docker setup (optional)
tests/                    → Automated smoke tests






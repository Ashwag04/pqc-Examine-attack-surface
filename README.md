# PQC Attack Surface — [Team Name]
Short description: Code and experiments for "Examining the Attack Surface of PQC".

# Project goal:
Study and demonstrate the attack surface of Post-Quantum Cryptography (PQC) by (1) building small, toy implementations to learn internal data flows and (2) running reproducible algorithmic/implementation experiments (brute-force, simulated side-channel) that illustrate how parameter choices and coding mistakes reduce security.

## Repo layout — what each part is for
README.md
requirements.txt         # declared Python deps (oqs can fail on Windows; see notes)
src/
  ├─ toy_kem.py          # pedagogical toy KEM (generate/encaps/decaps) — run now
  └─ kyber_example.py    # real KEM example (liboqs) — run in WSL/Docker
experiments/
  └─ bruteforce/
      └─ run_bruteforce.py  # exhaustively brute-force toy_kem secret (12/14/16 bits)
docs/                    # reading list, SOPs, ethics (add team notes here)
data/                    # pointers/links to raw traces (do NOT commit large files)
notebooks/               # Jupyter notebooks for analysis and plots
.github/ISSUE_TEMPLATE/  # experiment issue template
docker/                  # optional Dockerfile for reproducibility
tests/                   # optional smoke tests

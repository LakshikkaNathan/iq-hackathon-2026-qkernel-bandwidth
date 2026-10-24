# Metal / non-metal classification with quantum kernels

Interstate Quantum Hackathon 2026, QML track

| | |
|---|---|
| Group name | Bandwidth Matters |
| Member | Lakshikka Sithamparanathan (solo) |
| Affiliation | Cleveland State University |
| Department | Department of Computer Science |
| Career level | PhD student |
| Category | Champion |

**Report:** [PDF](REPORT.pdf)

A quantum-kernel SVM that classifies chemical elements as metal or non-metal, with a study of kernel bandwidth, exponential concentration, shot noise, feature maps and noise on IBM hardware (ibm_kingston).

## Files

| path | content |
|---|---|
| `qkernel_bandwidth.ipynb` | all code, with outputs from the full run |
| `REPORT.md`, `REPORT.pdf` | project report |
| `data/elements.csv` | element dataset (from the `mendeleev` database) |
| `figures/` | all figures |
| `results/` | result tables (CSV) and the ibm_kingston hardware results with job IDs (`hw_*`) |
| `requirements.txt` | package versions |

## Running the notebook

Open `qkernel_bandwidth.ipynb` (for example in Google Colab) and run all cells; the first cell installs the packages.

- `FAST = True` runs a quick check (about 5 min); `FAST = False` runs the full study (about 1 h).
- `RUN_HARDWARE = False` (default) loads the saved hardware results from `results/`, so no IBM account is needed.

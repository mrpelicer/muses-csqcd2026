**MUSES Tutorial Notebook**

This repository contains the hands-on notebook for the MUSES Calculation Engine session at CSQCD 2026.

## Run in Google Colab

Click below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mrpelicer/muses-csqcd2026/blob/main/muses_tutorial.ipynb)

Then run the first setup cell.

## What this tutorial covers

1. Running a CMF → Lepton → QLIMR workflow.
2. Running a Crust-DFT → Lepton → QLIMR workflow.
3. Combining Crust-DFT and CMF with Synthesis.
4. Downloading and reading Calculation Engine output files.
5. Plotting equations of state and neutron-star mass-radius curves.

## Requirements

No local installation is needed if using Google Colab.

You will need:

- A web browser.
- A MUSES Calculation Engine account.
- A MUSES CE API token.

## Local usage

```bash
git clone https://github.com/mrpelicer/muses-csqcd2026.git
cd muses-csqcd2026
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab muses_tutorial.ipynb
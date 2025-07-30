# MEG-EEG Analysis

This repository provides an example workflow for analyzing EEG (and MEG) data using [MNE-Python](https://mne.tools/). The workflow demonstrates how to load sample data, visualize raw signals and power spectral density, and perform basic preprocessing such as ICA.

---

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Example Usage](#example-usage)
- [Key Steps](#key-steps)
- [References](#references)
- [License](#license)

---

## Overview

This project includes a Jupyter Notebook that guides you through:

- Loading sample EEG/MEG data from the MNE sample dataset
- Printing raw data info and data structure
- Plotting power spectral density (PSD) and raw signals
- Preprocessing data (ICA for artifact removal)

---

## Requirements

- Python 3.8 or newer
- Jupyter Notebook
- [MNE-Python](https://mne.tools/stable/install/index.html)
- numpy
- matplotlib

Install the requirements with:

```bash
pip install mne numpy matplotlib jupyter

# SimDAT2D

A 2D X-ray pattern generator using PyFAI created by the [Butala Research Group](https://github.com/ButalaResearchGroup) (specifically Danielle N. Alverson) to simulate thin film data deposited onto single crystal substrates. Additional information on use in [2025 manuscript and SI](https://doi.org/10.1107/S2053273325002438).

![Alt text](SimDAT2D/sim.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [License](#license)

## Introduction

The SimDAT2D program can be used to generate synthetic X-ray scattering data from two or more distinct scattering contributions (e.g., isotropic, diffuse, and anisotropic). Each contribution is generated individually and combined as a linear combination into a single simulated 2D detector image. This allows for the relative intensities of each to be varied and for each signal to be independently known.

## Features

- Isotropic Scattering through Calibrants
- Anisotropic Scattering 
- Combination for Synthetic Thin Film 2D 
- Rotation and Integration
- Mask Creation

## Getting Started

Instructions on how to clone, and get the project running locally.

```bash
# Clone the repository
git clone https://github.com/dnalverson/SimDAT2D

# Change into the project directory
cd SimDAT2D

# Install dependencies
pip install -e . --use-pep517 

# Start the project
import SimDAT2D as sim

```

Please see the [tutorial notebook](Tutorial.ipynb) for more information.

## License

This project is licensed under the [BSD 3-Clause License](https://spdx.org/licenses/BSD-3-Clause-Clear.html) - see the [LICENSE](LICENSE.md) file for details.

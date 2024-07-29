# VERTECS Camera Control Board
[![Website](https://img.shields.io/website?down_message=unavailable&up_color=blue&up_message=VERTECS%20Project&url=https%3A%2F%2Fwww.vertecs-project.com)](https://www.vertecs-project.com)
[<img alt="GitHub License" src="https://img.shields.io/github/license/ezrafielding/VERTECS-CCB">](https://github.com/ezrafielding/vertecs-ccb/blob/main/LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.1117/12.3019471)](https://doi.org/10.1117/12.3019471)
[![arXiv](https://img.shields.io/badge/arXiv-2406.00935-b31b1b.svg)](https://arxiv.org/abs/2406.00935)

<img src="https://vertecs-project.com/wp-content/uploads/2023/07/VERTECS-2048x2048.png" alt="VERTECS Logo" width="200"/>
Welcome to the VERTECS Camara Control Board (CCB) project! This is an open-source hardware project designed to provide a flexible and robust payload interface for 6U nanosatellites.


## Introduction
The VERTECS CCB, is an open-source payload interface board leveraging Commercial Off-The-Shelf (COTS) components with a Raspberry Pi Compute Module 4 at its core. Originally developed for the [VERTECS 6U Astronomical Nanosatellite](https://www.vertecs-project.com), the board has been opened-sourced and made available for use in future nanosatellite projects.

<img src="https://github.com/ezrafielding/vertecs-ccb/blob/main/docs/images/CCB_front.jpg" alt="CCB Front" width="350"/> <img src="https://github.com/ezrafielding/vertecs-ccb/blob/main/docs/images/CCB_back.jpg" alt="CCB Back" width="350"/>

More information can be found in the [conference paper](https://arxiv.org/abs/2406.00935) for the VERTECS CCB.

## Getting Started
### Prerequisites
- [KiCAD 7](https://www.kicad.org/) installed to access PCB design files.

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/ezrafielding/vertecs-ccb.git
   ```
2. Open the KiCAD project file in the VERTECS_CCB directory.

## Citation
Ezra Fielding, Victor H. Schulz, Keenan A. A. Chatar, Kei Sano, Akitoshi Hanazawa, "VERTECS: A COTS-based payload interface board to enable next generation astronomical imaging payloads," Proc. SPIE 13101, Software and Cyberinfrastructure for Astronomy VIII, 131010J (25 July 2024); https://doi.org/10.1117/12.3019471
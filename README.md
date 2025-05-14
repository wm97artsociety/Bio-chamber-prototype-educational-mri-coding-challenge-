# BioCell Recalibration Chamber (BRC-1) MRI-Compatible Control Software

## Overview
This software package is designed to simulate and control the BioCell Recalibration Chamber (BRC-1) functionality in a simulated environment compatible with MRI machines. It includes modules to interface with the MRI hardware, generate bio-frequency signals, simulate atom/molecule infusion, manage nutrient formulas, and simulate electrical press plate synchronization. The software also includes a virtual MRI test suite to ensure compatibility with MRI protocols.

## Key Features
- **MRI Interface**: Simulated MRI hardware connection and data exchange.
- **Frequency Generator**: Control bio-frequency pulse generation (e.g., 528 Hz for DNA repair, 7.83 Hz for grounding).
- **Atom/Nutrient Delivery**: Simulated infusion of CBG, EGCG, Resveratrol, and other molecules based on formulas.
- **Electric Press Plate**: Simulation of neural reset and cardiac sync via chest plate activation.
- **Virtual MRI Test**: Ensures no interference with MRI protocols, providing a safety check for MRI compatibility.

## Requirements
- Python 3.x
- Required Python packages: `numpy`, `matplotlib` (for simulation visualization, if needed)
- MRI hardware connection (simulated in this package)

## Installation
1. Download the source code from this repository.
2. Install Python 3.x if not already installed.
3. Install dependencies by running:
    ```
    pip install -r requirements.txt
    ```
4. Run the main script with:
    ```
    python main.py
    ```

## License
This software is released under the MIT License. You can freely modify and distribute it for personal or commercial use, provided you give appropriate credit.

## DISCLAIMER
This software is for simulation purposes only and is not intended for use with actual medical equipment. Use at your own risk.

## Authors
- Developed by wm97 
- Based on the BioCell Recalibration Chamber concept design

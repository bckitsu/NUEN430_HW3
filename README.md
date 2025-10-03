# README

## Overview
This repository implements a 1D/2D-aware finite-volume solver for the steady-state, one-group diffusion equation with fixed source on Cartesian grids.

## Requirements
- Python 3.8+
- NumPy
- SciPy
- Matplotlib

## Files
- `mesh.py`: Mesh2D class for uniform refinement and material map.
- `materials.py`: MatProps class for material properties via dicts or functions.
- `solver.py`: DiffusionSolver2D class to assemble and solve the FV system.
- `main.py`: Examples:
  1. Method of Manufactured Solutions (constant coeff) with error table.
  2. 1D ABA slab heterogeneous case.
  3. 2D checkerboard heterogeneous case.

## Usage
Run:
```
python main.py
```
This prints the MMS error table and displays plots for the 1D slab and 2D checkerboard.

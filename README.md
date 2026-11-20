# Hydraulics & Fluid Mechanics in Python (`hydraulics-python`)

A collection of computational fluid mechanics and hydraulic engineering models written in Python. This repository applies numerical methods (`NumPy`) and scientific visualization (`Matplotlib`) to analyze closed-conduit pipe flow, frictional head loss formulations, and pump-system matching.

## Repository Structure

| Module | Description | Key Concepts |
| :--- | :--- | :--- |
| **[01 — Head Loss Comparison](.01_Hazen_Williams_VS_Darcy_Weisbach)** | Parametric benchmark comparing empirical vs. physics-based friction loss models across turbulent flow regimes ($Re \approx 6.34 \times 10^4$ to $2.54 \times 10^5$). | Hazen-Williams, Darcy-Weisbach, Swamee-Jain explicit friction factor, pipe roughness ($\epsilon/d$) |
| **[02 — Pump Duty Point Analysis](./02_pump_duty_point)** | Numerical determination of the steady-state operating point for a centrifugal pump coupled to a pressurized piping system. | System resistance curves, pump performance interpolation, duty point intersection |

## Dependencies & Setup

All scripts and notebooks require Python 3.8+ along with `numpy` and `matplotlib`:

```bash
pip install numpy matplotlib
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/tutorbosun/hydraulics-python.git
   cd hydraulics-python
   ```
2. Navigate into any module folder and run the Python script or Jupyter Notebook to reproduce the numerical tables and high-resolution plots.

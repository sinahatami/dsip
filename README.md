# Digital Signal and Image Processing (DSIP) Portfolio

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

This repository contains my coursework, assignments, and final project for the **Digital Signal and Image Processing (DSIP)** course at the **University of Genova**. It demonstrates practical implementations of signal processing algorithms, frequency domain analysis, and predictive filtering using Python.

---

## 📁 Repository Structure

The project has been refactored into a clean, consolidated workspace to improve readability and maintainability.

```text
dsip/
│
├── assignments/                  # Core lab exercises focusing on signal processing fundamentals
│   ├── Lab 1 - Fourier series.ipynb        # Signal decomposition and Gibbs phenomenon
│   ├── Lab 2 - Fourier Transform.ipynb     # Frequency domain analysis
│   ├── Lab 3 - Filters.ipynb               # Digital filter design and audio signal filtering
│   └── Lab 4 - Kalman.ipynb                # Kalman filtering for state estimation and tracking
│
├── project/                      # Comprehensive final project integrating course concepts
│   ├── final_project.ipynb                 # Implementation, analysis, and experiments
│   └── final_project.pdf                   # Final project report and detailed methodology
│
└── README.md                     # Project overview and instructions
```

---

## 🔬 Core Topics Covered

1. **Fourier Series & Decomposition**
   - Investigating signal approximations using sines and cosines.
   - Analyzing the **Gibbs Phenomenon** and the effects of varying harmonic components on overshoot and undershoot behavior.

2. **Fourier Transform & Frequency Analysis**
   - Transforming signals from the time domain to the frequency domain.
   - Utilizing $\delta$ (Dirac) functions to interpret signal components and peak frequencies.

3. **Digital Filtering**
   - Designing filters (Low-pass, High-pass, Band-pass) and understanding their frequency response.
   - Practical application of filters to real-world audio signals to isolate frequency bands.

4. **Kalman Filtering**
   - Implementing naive and advanced Kalman Filters for time-series and state prediction.
   - Estimating hidden state variables from noisy observations in stochastic systems.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have a working Python environment (Python 3.8+ recommended). To install the required dependencies to run the notebooks, execute:

```bash
pip install numpy scipy matplotlib pandas filterpy jupyter nbmake
```

### Usage

You can launch the Jupyter notebooks locally to explore the code, re-run experiments, or visualize the signal plots:

```bash
jupyter notebook
```

Navigate to the `assignments/` or `project/` directory and open the `.ipynb` files to begin.

---

## 📈 Final Project

The `project` directory contains the final comprehensive analysis for the DSIP course. It integrates topics learned throughout the semester, featuring detailed visualizations, mathematical foundations, and real-world signal/image processing applications. The complete written report is available as `final_project.pdf`.

---

## 🛠️ Maintenance and Refactoring

This repository was recently audited and professionalized:
- **Consolidation**: Merged multiple sub-repositories into a single, cohesive project structure.
- **Data Integrity**: Repaired JSON serialization errors in older Jupyter Notebooks caused by improper HTML formatting.
- **Code Modernization**: Updated deprecated NumPy API calls (e.g., `np.float` $\rightarrow$ `float`) to ensure compatibility with NumPy 2.0+.
- **Validation**: All notebooks have been programmatically executed end-to-end to verify correctness.

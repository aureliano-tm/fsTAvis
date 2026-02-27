# fsTAvis

**fsTAvis** is a collection of Jupyter Notebooks written in Python for the processing, visualization, and analysis of femtosecond and nanosecond transient absorption (fs/ns-TA) spectroscopy data.

---

## Overview

The notebooks are designed to provide a lightweight and flexible workflow for handling ultrafast transient absorption datasets, including preprocessing, spectral inspection, and data visualization.

---

## Installation and Setup

1. Download or clone this repository.
2. Switch to the specific branch corresponding to your experimental configuration.
3. Ensure a working Python environment with Jupyter Notebook installed.

---

## Standard Usage Workflow

### 1. Prepare Data Directory
Move the `.ipynb` notebook file into the **root directory of your data folder**.

### 2. Preprocessing
Run the preprocessing cell in the notebook.  
This step generates processed scan files, which will be automatically saved in the folder:

### 3. Data Cleaning and Correction
Use **Surface Xplorer** to perform:
- Removal of unwanted spectra
- Chirp correction
- Time-zero correction
- Temporal and spectral cropping

After processing, export the corrected data files back to the **root directory**.

Surface Xplorer (Ultrafast Systems):  
https://ultrafast.systems/products/spectrometers-accessories/surface-xplorer/

### 4. Restart the Notebook
Clear all outputs and restart the kernel (recommended).  
This step helps release system resources and ensures a clean analysis environment.

### 5. Visualization and Analysis
Re-import the required libraries and execute the visualization and analysis cells in the notebook.

### 6. Enjoy
Explore and visualize your transient absorption data.

---

## Notes

- Clearing outputs and restarting the kernel between preprocessing and visualization is recommended for optimal performance.
- The workflow is modular and can be adapted for different experimental setups.

---

## License
This project is licensed under the MIT License.

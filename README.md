# fsTAvis

**fsTAvis** is a collection of Jupyter Notebooks written in Python for the processing, visualization, and analysis of femtosecond and nanosecond transient absorption (fs/ns-TA) spectroscopy data.

---

## Preview

### Data Visualization
2D Plot of Entire Data
<img width="1610" height="1182" alt="1" src="https://github.com/user-attachments/assets/091cedc6-f210-4803-b560-411c00d80a66" />
1D Plot of Extracted Spectra
<img width="1586" height="1186" alt="2" src="https://github.com/user-attachments/assets/0618534c-c73c-4a15-b29b-716ace4cac7c" />
1D Plot of Extracted Kinetics
<img width="1352" height="972" alt="3" src="https://github.com/user-attachments/assets/9cd66c31-3ea8-4ea3-8332-3777a3ae766f" />

### Data Analysis
Single Wavelength Fitting
<img width="1590" height="1184" alt="7" src="https://github.com/user-attachments/assets/d211b78b-6db9-4097-a27d-1f1f9e4750f3" />
Global Fitting
<img width="1964" height="694" alt="5" src="https://github.com/user-attachments/assets/2407a689-fed9-4330-b611-686b43204464" />
<img width="1998" height="770" alt="4" src="https://github.com/user-attachments/assets/e1a63b09-ed43-4329-bfdc-afaa9e6d7fa9" />
<img width="868" height="546" alt="6" src="https://github.com/user-attachments/assets/ddce3ffa-0729-4914-81e2-9d27d5269e89" />

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

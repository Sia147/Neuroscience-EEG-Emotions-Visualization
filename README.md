# 🧠 Neuroscience EEG Visualization: Emotional Mind States

A Neuroinformatics project focused on processing, analyzing, and visualizing multi-dimensional electrophysiological (EEG) brain signals to decode human emotional states.

---

## 🚀 Project Overview
This project bridges the gap between data science and clinical neuro-computing. By leveraging structural datasets and signal transformation principles, we successfully process raw brain activity and high-dimensional Kaggle features to identify baseline patterns behind human emotions (Positive, Negative, and Neutral).

---

## 🛠️ Key Milestones Achieved

### 1. Raw EEG Signal Processing & Spatial Mapping
* Utilized the **MNE-Python** library to manipulate and clean research-level multi-channel brainwave formats (`.fif`).
* Generated **2D Time-lapse Brain Topomaps** (heatmaps) to view cortical voltage distributions over milliseconds right after a visual/auditory stimulus.

### 2. High-Dimensional Kaggle Data Analysis
* Processed Jordan Bird's **"EEG Brainwave Dataset: Feeling Emotions"** featuring **2,132 records and 2,549 features**.
* Decoded the biological infrastructure of features (Mean statistical values, Fast Fourier Transforms (FFT), and brain wave frequencies like Alpha, Beta, Theta, Delta, and Gamma).

### 3. Chronological Power Spectrum Analytics
* Plotted custom time-series line graphs tracking frequency amplitudes up to 50 Hz.
* Discovered real-world neurological shifts showing that **Negative Emotions (anger/fear)** produce wilder, high-amplitude electrical fluctuations on temporal channels compared to baseline positive states.

### 4. Brain Region Functional Synchronization
* Computed statistical Pearson correlation matrices using Seaborn heatmaps.
* Isolated inverse activation dynamics and front-hemispheric symmetries between frontal lobe electrodes.

---

## 💻 Technical Stack Used
* **Programming Language:** Python 3.14
* **Neuroscience Domain Library:** MNE-Python
* **Core Analytics Framework:** Pandas, NumPy
* **Data Visualization Suites:** Matplotlib, Seaborn
* **Development Environments:** Jupyter Notebook, Kaggle Notebooks

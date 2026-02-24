# EEG Artifact Removal using ICA (MNE-Python)

This project demonstrates preprocessing of real human EEG recordings using MNE-Python.

Steps performed:
1. Loaded PhysioNet EEG Motor Movement dataset
2. Visualized raw EEG signals
3. Applied band-pass filtering (1–40 Hz)
4. Performed Independent Component Analysis (ICA)
5. Detected and removed eye-blink (EOG) artifacts
6. Compared EEG signals before and after cleaning

The goal is to obtain clean neural signals suitable for Brain-Computer Interface (BCI) and cognitive neuroscience analysis.

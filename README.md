# EEG Artifact Removal using ICA (MNE-Python)

This project implements an EEG preprocessing pipeline for artifact removal and signal enhancement using MNE-Python.

## Methods
- Bandpass filtering (1–40 Hz)  
- Independent Component Analysis (ICA) for artifact separation  
- Detection and removal of EOG (eye-blink) artifacts  

## Dataset
- PhysioNet EEG Motor Movement dataset  

## Results
- Improved signal clarity after artifact removal  
- Reduced noise validated through spectral analysis (PSD)  

## Conclusion
Effective preprocessing using ICA is essential for reliable EEG analysis, particularly for downstream tasks such as BCI and neural decoding.

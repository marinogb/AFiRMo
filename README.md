# AFiRMo

Early warning of atrial fibrillation from RR interval dynamics using deep learning.

This repository contains the initial research code used to develop and evaluate a neural network for predicting atrial fibrillation (AF) before onset from RR intervals. The implementation uses a representative subset of patients from the open-source [PAF Prediction Challenge Database](https://physionet.org/content/afpdb/1.0.0/) on PhysioNet.

This repository corresponds to the earlier research version of the project that supported the initial preprint.

## Related publication

Initial preprint version:
- Gavidia et al., *Early warning of atrial fibrillation using deep learning*, medRxiv, 2022.

Final peer-reviewed version:
- Gavidia et al., *Early Warning of Atrial Fibrillation Using Deep Learning*, **Patterns** (2024), DOI: 10.1016/j.patter.2024.100970

## Note

This repository contains the earlier implementation used for the initial research and preprint stage.

The updated codebase associated with the final published version is available here:
- [WARN repository](https://github.com/marino-gavidia/WARN)

## Dependencies

This code was tested with:
- Python 3.9.12
- TensorFlow 2.8
- MATLAB R2020a

## Main files

- `main.m`  
  Generates the processed data used for training and prediction.

- `train&predict.py`  
  Trains the neural network and runs predictions.

## Summary

This project focuses on transforming ECG-derived RR interval data into a representation suitable for deep learning, with the goal of detecting early warning patterns that precede atrial fibrillation episodes.

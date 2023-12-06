# PHY 381C Final Project
## **Generative Model of Lux-Zeplin Detector Electronic Response** ##
### *Chloe O'Brien and Gregory Sehr* ###
This repository is contains data processing and machine-learning training code, which takes in Lux-Zeplin (LZ) Detector Electronic Response (DER) output as input and trains a Conditional Variational Auto Encoder (CVAE) to build a generative model that can generate DER waveforms from raw PMT photon data.  As the DER code is computationally intensive, this model intends to allow for quickened simulation of DER waveforms.

---
### Requirements:
Python
Jupyter Notebook
*Package requirements listed within files*
### Usage:
1. Run `dataCleaning.ipynb` to process input ROOT file and output a Pandas DataFrame to CSV, located in `./data_clean`
2. Run `training.ipynb` to process the DataFrame through the CVAE

*Note: some further instructions included in each file*

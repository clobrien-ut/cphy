
# PHY 381C Final Project
## **Generative Model of Lux-Zeplin Detector Electronic Response** ##
### *Chloe O'Brien and Gregory Sehr* ###
This repository is contains data processing and machine-learning training code, which takes in Lux-Zeplin (LZ) Detector Electronic Response (DER) output as input and trains a Conditional Variational Autoencoder (CVAE) to build a generative model that can generate DER waveforms from raw PMT photon data.  As the DER code is computationally intensive, this model intends to allow for quickened simulation of DER waveforms.

---
### Requirements:
Python \
Jupyter Server/Notebook \
*Note: Package requirements listed within files* 

### Usage:
1. Access data via UTBox folder https://utexas.app.box.com/folder/238524022917.  If you do not have access but are authorized, contact repo owner at clobrien@utexas.edu.
	* Input (DER Output) data is stored in `input_data` folder.
	* Output (processed DataFrames) data is stored in `data_clean` folder.
2. If processing your own files, run `dataCleaning.ipynb` to process input ROOT file(s) and output a Pandas DataFrame to CSV, located in `./data_clean`.  If not, skip to step 3.

4. Run `training.ipynb` to process the DataFrame files stored in `data_clean` through the CVAE.

*Note: some further instructions included in each file*

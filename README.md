# Efficient-CryoElectron-Tomogram-Simulation-classification-experiments
## Convolutional Neural Network based Classification Method:

This code repository has experimenation code and results published in the article 'Efficient Cryo-Electron Tomogram Simulation of Macromolecular Crowding with Application to SARS-CoV-2'. 

In order to validate that the simulation approach formulated in the paper can be used to assist cryo-ET analysis, we generated a dataset containing 15,000 samples, and used it to train and test two cryo-ET classification methods. This repository contains the code and results for the 'CNN based approach'.

### Dataset Used:
We used three datasets of subtomograms of 32^3 voxels. Each dataset had different SNR levels. The SNRs used were 0.03, 0.05 and positive infinity respectively. In each set, we obtained 5000 subtomograms of 10 classes. The 10 types of macromolecules and an example of the corresponding simulated cryo-ET slice could be found in the following figure:

<p align="center">
  <img src="data.png" width="500" height="300"  />
</p>


### Model Architecture:

<p align="center">
  <img src="modelarchitecture.png" width="200" height="500"  />
</p>

### Results:
The following table shows the results obtained from our experiments on the Cryo-ET data. The 3D CNN architecture shows better results in all three noise environments.
<p align="center">
  <img src="results.png" width="200" height="200"  />
</p>

### Citation

@INPROCEEDINGS{9313185,
  author={Liu, Sinuo and Ma, Yan and Ban, Xiaojuan and Zeng, Xiangrui and Nallapareddy, Vamsi and Chaudhari, Ajinkya and Xu, Min},
  booktitle={2020 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)}, 
  title={Efficient Cryo-Electron Tomogram Simulation of Macromolecular Crowding with Application to SARS-CoV-2}, 
  year={2020},
  volume={},
  number={},
  pages={80-87},
  doi={10.1109/BIBM49941.2020.9313185}}

### Published Work

Click [here](https://ieeexplore.ieee.org/abstract/document/9313185) to access the published research paper.

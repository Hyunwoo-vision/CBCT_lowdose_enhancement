# CBCT_lowdose_enhancement
- This repository is about enhancement of CBCT based lowdose CT image
- We developed lowdose protocol of our CBCT using binning mode and mA modulation
- As a result, the quality lowdose images were extremely dergaded 
- Therefore we are proposing deep learning based lowdose CBCT image enhancement method



## Dataset
- Normally the lowdose protocol not have been used in real fields
- For this reason, imblance between normal dose dataset and low dose dataset is severe
- Therefore we simulated low dose ct images from normal dose images for supervised learning
- The flow of simulating low dose ct images is displayed below

![datasetflow](https://user-images.githubusercontent.com/65393045/207760298-e3450ce9-b44c-4273-959c-086e2b4871de.png)



## Model architecture 
- Enhancement of lowdose CT task is related to super-resolution either in terms of restoring detail structures
- So in this study we referenced the model which is SOTA in super-resolution and denoising field
- The referenced model is RRDBnet(Residual in Residual Dense Block Network) which is displayed in below

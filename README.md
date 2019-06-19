# Multispectral Parameter Estimation
## **Folder Descriptions**
- **Inputs_ippg**
This folder contains both the multispectral data and the ground truth data necessary.
- **Outputs_ippg**
This folder contains the ippg predictions for the input data given. 

## **File Descriptions**
- **MultiSpectral.py**
    This file is the main file which contains all the functions for implementing ICA, PCA, FFT, Filtering and Data loading. The inputs to this file are from Inputs_ippg and outputs are written to Outputs_ippg folder.

- **InputAnalysis.py**
    This file has functions for plotting input data, fft data and ICA data which should be enabled from MultiSpectral.py. 

- **Downsample.py**
    This file implements downsampling of video file. Input to this is the video csv and Output is the same folder.The downscale factor can be set in code to set the downsampling rate.

- **CreateCsvData.py**
    It converts the raw video captured by the multispectral camera to csv format data.
    
- **TextToCSV.py**
     This file converts .txt file formats to .csv format. Path for the input and output files needs to be specified in the code.





# MaLeFiSenta1
This reflects the following work:
D. Alina, A. Shomanov and S. Baimukhametova, "MaLeFiSenta: Machine Learning for FilamentS Identification and orientation in the ISM," in IEEE Access, 2022, doi: 10.1109/ACCESS.2022.3189646.

Contains 
- data preparation
- models settings 
- optimization procedures of the neural networks for filameent identification and orientation
- MSSIM computation

Details:
This is not a fully automatized code. 
One should define data directories and build the training datasets.
This code then prepares the datasets for the neural network models.
The models set-up are also presented : Mask RCNN and Unet.
The optimization procedures are also included.
Moreover, the Morphologcal Similarity Index Measurement functions (Wang et al.2005, Green et al.2017) are also included which allows a user to make comparison, if necessary.
The models saving is also included.

Update (Jul 29, 2023):
due to the inconsistencies between the recent distributions of tensorflow and maskrcnn, we recommend the following solution: see  https://github.com/KenessaryMurat/Mask-R-CNN-for-Filaments-Identification.git

Update (Aug 17, 2024):
the latest version, with the compiled jupyter notebook and  model weights is located here: https://github.com/Temirkul/ism-filaments-analysis

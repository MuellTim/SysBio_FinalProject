# SysBio_FinalProject

This is a project in the modul: "Systems Biology: Computational Analysis and Interpretation of High-throughput Data" at the HU Berlin.

The training and analysis of the PBMC3K and PBMC68K (downloaded from https://bioconductor.org/packages/devel/data/experiment/vignettes/TENxPBMCData/inst/doc/TENxPBMCData.html) datasets are given in the Notebooks: 

Analysis_PBMC3K.ipynb
Analysis_PBMC68K.ipynb 


The Neural Network is writen in PyTorch and the implementation is based and adapeded by me: ( https://sannaperzon.medium.com/paper-summary-variational-autoencoders-with-pytorch-implementation-1b4b23b1763a and https://towardsdatascience.com/understanding-variational-autoencoders-vaes-f70510919f73)

Most of the data handling is done in Scanpy, and the Scanpy tutorial is the basis of the filtering: https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html

All trained models are saved and can be found here so that training does not have to be repeated.



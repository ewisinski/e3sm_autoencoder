# Multi-Branch $\beta$-Variational Autoencoder for Tropical Pacific Variability

*Repository Authors: Emily Faith Wisinski (University of Maryland, College Park) and Maria J. Molina (University of Maryland, College Park)*

## Table of Contents

This GitHub repository serves as a software and data access point for the paper titled "What's in the latent space? Exploring coupled tropical Pacific variability within a Multi-branch $\beta$-Variational Autoencoder" by Wisinski et al. (2026). Below is a description of what is included within each folder in the repository, and a short description for how to use it. Thanks for visiting!

*Figures*
- This folder contains all of the figures included in the current version of the paper. There are 16 figures in the main body of the text and 1 figure in the Appendix. The figures are clearly labeled and include the date they were created.

*Enivronment*
- This folder contains a .yml file that was used to run the analysis for this paper. This environment leverages an older version of Keras (2.15), which allows distinct tracking of the three separate loss terms of the variables in the custom loss layer. Using a newer version of Keras will not allow you to do this tracking!

*VAE*
- Jupyter notebook containing code for the $\beta$-VAE model architecture and training. The input data is located within the folder labeled 'data'. The various hyperparameters are outlined in Table 1 of the paper and can be manipulated to test various architectures.
- Jupyter notebook for the $\beta$-VAE variance share per latent dimension. This code corresponds to Figure 3.

## CSV Data Source

Some Juptyer notebooks leverage .csv data for SST, OHC, and OLR train/test scaled inputs. These files are too large to be stored in this repository, but can be found here: https://doi.org/10.5281/zenodo.19390030

## Software and Acknowledgement

We would like to acknowledge the use of the Derecho system (doi:10.5065/qx9a-pg09) supported by the NSF National Center for Atmospheric Research (NCAR) at the NSF NCAR-Wyoming Supercomputing Center, sponsored by the National Science Foundation and the State of Wyoming.
- Computational and Information Systems Laboratory. 2023. Derecho: HPE Cray EX System (University Community Computing). Boulder, CO: NSF National Center for Atmospheric Research. doi:10.5065/qx9a-pg09.
- Wisinski, E. F., Molina, M. J. M., Hall, K. J. C., Bao, H., Mahajan, S., Rosenbloom, N., & Fasullo, J. (2026). CSV Data for 'What's in the latent space? Exploring coupled tropical Pacific variability within a Multi-branch β -Variational Autoencoder' (v1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.19390030
- Paper and preprint citation forthcoming.

# PLoSCompSomiteClockNoise
Sample of data from the PLoS Computational Biology Paper, 'Stochastic Regulation of her1/7 Gene Expression is the Source of Noise in the Zebrafish Somite Clock Counteracted by Notch Signalling'.

The subfolder, 'ExperimentalData', includes example embryo images relating to the analysis in figures 4E and F. The data is stored as separate tif files for each slice of the 3D image and each channel (nuclei and her1 mrna).

The subfolder 'NumericalData, includes a sample of data generated via our hybrid Gillespie Algorith Delay Differential Equation mathematical model. The data is stored in MATLAB data files with each subfolder corresponding to the Figure in the paper the data was generated for. The majority of files contain only the Her1 protein levels. However, the data for Figure 2D (stochastic gene regulation in the absence on Notch signalling) and Figure 5 (stochastic gene regulation in the presence of Notch signalling) includes all the gene, mrna and protein data for each simulation. All mrna and protein levels have been interpolated (due to the large population levels) to save storage space whilst the populations of genes in each state are presented as they were generated (such that the timings of stochastic gene regulation can be analysed).

# Biologically-Plausible-Model-of-LGN-V1-Pathways
This MATLAB project models LGN-V1 pathways with feedforward and feedback connections of excitatory (positive) and inhibitory (negative) types based on efficient coding.

Author: Yanbo Lian
Date: 26/02/2019

Citation: Lian Y, Grayden DB, Kameneva T, Meffin H and Burkitt AN (2019) Toward a Biologically Plausible Model of LGN-V1 Pathways Based on Efficient Coding. Front. Neural Circuits 13:13. doi: 10.3389/fncir.2019.00013 (https://doi.org/10.3389/fncir.2019.00013)

'LGN_V1_UpDown_PosNeg.m' is the main script that runs the whole thing.

'Compute_S_U_LGN_V1_UpDown.m' is a function, that computes model responses, called by 'LGN_V1_UpDown_PosNeg.m'.

'NormalizeA.m' is a function that normalizes a matrix.

'DisplayA.m' is a function that can displays many pictures with the same size at the same time.

'Green2Magenta.m' and 'scm.m' are functions that define colorcodes for plotting figures.

'IMAGES.mat' is the Pre-whitened natural images used to train the model (downloaded from http://www.rctn.org/bruno/sparsenet/).

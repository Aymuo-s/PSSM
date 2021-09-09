# PSSM
Protein secondary structure prediction using SVM and testing using Porter server.

Given a protein sequence, the secondary structure prediction problem is to predict whether each amino acid is in a helix, strand or neither. H, E and C represent helix, strand and non-routine structure, respectively
Prediction of the secondary structure of the protein cannot be done with the input at position i alone, but must be accompanied by other amino acids on the left and right side of the input position i. So here sliding window technique can be used.
Sliding Window will be used to capture several ammino acids in primary sequence and use it as input for the classification model.

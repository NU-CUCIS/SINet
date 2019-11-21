# SINet

SINet is an acronym for SMILES-InChI Neural Network. We present a multi-input single-output neural network that utilizes two text-based representations SMILES and InChI for representing molecules as inputs to the neural network for predicting chemical properties. In this work, we restrict ourself to the use case of organic solar cells, and the target variable is highest occupied molecular orbital energy for donor molecules. We first pre-train our neural network on a large DFT computed dataset of hypothetical molecules, and then further train on smaller candidate datasets. 



## Requirements: 
1. Keras 2.0 or higher
2. Tensorflow 1.7 
3. RDKit 2017.09.1
4. Scikit-Learn 0.19.1
5. Numpy 1.14
6. Pandas 0.22

## Developer Team

The code was developed by the <a href="http://cucis.ece.northwestern.edu/">CUCIS</a> group at the Electrical and Computer Engineering Department at Northwestern University. 


## Citation
If you use this code or data, please cite:

A. Paul, D. Jha, W. Liao, A. Choudhary and A. Agrawal. Transfer Learning Using Ensemble Neural Nets for Organic Solar Cell Screening. International Joint Conference on Neural Networks, 2019, Link:  https://arxiv.org/abs/1903.03178

## Questions/Comments:

email: apaul@u.northwestern.edu<br/>
Copyright (C) 2019, Northwestern University.<br/>
See COPYRIGHT notice in top-level directory.

## Funding Support

This work was performed under the following financial assistance awards 70NANB14H012 and 70NANB19H005 from U.S. Department of Commerce, National Institute of Standards and Technology as part of the Center for Hierarchical Materials Design (CHiMaD). Partial support is also acknowledged from DOE awards DE-SC0014330, DE-SC0019358.

# ICA_NJ_BinarySeg



images + binary labels 

Data used in our paper: 
Chen Zhao, Aviral Vij, Saurabh Malhotra, Jinshan Tang, Haipeng Tang, Drew Pienta, Zhihui Xu, Weihua Zhou,
Automatic extraction and stenosis evaluation of coronary arteries in invasive coronary angiograms,

Computers in Biology and Medicine,

Volume 136,
2021,
104667,
ISSN 0010-4825,
https://doi.org/10.1016/j.compbiomed.2021.104667.
(https://www.sciencedirect.com/science/article/pii/S0010482521004613)

Abstract: Background
Coronary artery disease (CAD) is the leading cause of death in the United States (US) and a major contributor to healthcare cost. Accurate segmentation of coronary arteries and detection of stenosis from invasive coronary angiography (ICA) are crucial in clinical decision making.
Purpose
We aim to develop an automatic method to extract coronary arteries by deep learning and detect arterial stenosis from ICAs.
Methods
In this study, a deep learning model which integrates a feature pyramid with a U-Net++ model was developed to automatically segment coronary arteries in ICAs. A compound loss function which contains Dice loss, dilated Dice loss, and L2 regularization was utilized to train the proposed segmentation model. Following the segmentation, an algorithm which extracts vascular centerlines, calculates the diameters, and measures the stenotic levels, was developed to detect arterial stenosis.
Results and conclusions
In the dataset consisting of 314 ICAs obtained from 99 patients, the segmentation model achieved an average Dice score of 0.8899, a sensitivity of 0.8595, and a specificity of 0.9960. In addition, the stenosis detection algorithm achieved a true positive rate of 0.6840 and a positive predictive value of 0.6998 on all types of stenosis, which has great promise to advance to clinical uses and could provide auxiliary suggestions for CAD diagnosis and treatment.
Keywords: Coronary artery disease; Invasive coronary angiography; Image segmentation; Deep learning; U-net

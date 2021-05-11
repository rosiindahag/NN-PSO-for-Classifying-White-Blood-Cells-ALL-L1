## Feature Selection Algorithm
This is the feature selection algorithm using Binary Particle Swarm Optimization. The method of the feature selection is wrapped selection which this method use classifier to give the feedback of the performance of the feature selection. The wrapper classifier is the Support Vector Machine (SVM) classifier [1]. I implement PySwarm Library to ALL L1 white blood cells dataset and decided the selected feature from the feature selection results. There are total 29 features in the dataset contains :

| No.  | Features | Part of Cells | 
| :-------------: | :-------------: | :-------------: |          
| 1 & 13  | Area  | Cytoplasm, Nucleus  |
| 2 & 14  | Perimeter   | Cytoplasm, Nucleus  |
| 3 & 15  | Solidity   | Cytoplasm, Nucleus  |
| 4 & 16  | Granularity   | Cytoplasm, Nucleus  |
| 5 & 17  | Circularity   | Cytoplasm, Nucleus  |
| 6 & 18  | R Channel   | Cytoplasm, Nucleus  |
| 7 & 19  | G Channel   | Cytoplasm, Nucleus  |
| 8 & 20  | B Channel   | Cytoplasm, Nucleus  |
| 9 & 21  | Entrophy   | Cytoplasm, Nucleus  |
| 10 & 22  | Energy   | Cytoplasm, Nucleus  |
| 11 & 23  | Homogenity   | Cytoplasm, Nucleus  |
| 12 & 24  | Contrast   | Cytoplasm, Nucleus  |
| 25  | Ratio of Nucleus & Cytoplasm Area  | Others  |
| 26  | Ratio of Nucleus & Cytoplasm Perimeter   | Others  |
| 27  | Normalization Area   | Others  |
| 28  | Normalization Perimeter   | Others  |
| 29  | Eccentricity   | Others  |

The selected feature would be different per running. It depends of the performance of the classifier.

### Reference

1. Miranda L.J., (2018). PySwarms: a research toolkit for Particle Swarm Optimization in Python. Journal of Open Source Software, 3(21), 433, https://doi.org/10.21105/joss.00433

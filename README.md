# Cardiac-Action-Potential-Model-of-the-Human

This software code provides a model of the human cardiac action potential described in [1]. The model code is written in CellML which is an open standard based on the XML markup language [2]. The model was derived from voltage clamp experimental data from canine ventricular myocytes/tissue under nearly identical and physiological conditions. This model of the human action potential is moderately complex with six currents and seven variables, including a novel phenomenological model of dynamic diastolic calcium concentration (CaiD). The model was calibrated using the following well-known and important electro-physiological phenomena measured from patients during programmed electrical stimulation (PES): 1) action potential duration; and 2) take-off potential. The model was validated by comparing simulation results to several clinical studies including conduction speed, the ratio of effective refractory period and action potential duration, and arrhythmia induction during PES. The novelty of this model is that the voltage dependence of inactivation the rapid sodium current is an experimentally derived function of CaiD. This relationship allows for the action potential and conduction dynamics measured in patients during PES. For more information about the model please refer to [1]. There are a variety of OpenSource Tools to run this CellML model (see [2]).

The code itself is provided in the two files:

GrayFranzHumanModel2020_noCaiD.cellml & GrayFranzHumanModel2020_CaiD.cellml

Disclaimer: This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.

References

[1] Gray RA, Franz MR. A Model for Human Action Potential Dynamics In Vivo. American Journal of Physiology – Heart and Circulatory Physiology, 2020: doi.org/10.1152/ajpheart.00557.2019. https://journals.physiology.org/doi/full/10.1152/ajpheart.00557.2019 & https://pubmed.ncbi.nlm.nih.gov/31951472/


[2] CellML.Org

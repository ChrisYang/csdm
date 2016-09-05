<b>Continuous Supervised Descent Method - ACCV 2016</b>

This is the source code used to perform the experiments on face alignment for the following paper, to be published on december 2016 to the Asian Conference in Computer Vision:

Continuous Supervised Descent Method forFacial Landmark Localisation, M. Oliu, C. Corneanu, L. Jeni, J. Cohn, T. Kanade, S. Escalera. ACCV 2016

There you will find a complete description of the method and experimental results.

This source code contains the library developed for the project, implementing the proposed approach as well as SDM and Global SDM adapted to the statis case. It DOES NOT contain, because of its weight, the datasets used for the provided main files, but does contain the code to pre-process them, which is launched automatically if required, when running one of the main files. The two considered datasets are:

<b>300-W:</b><br/>
A common benchmarking dataset for facial landmark localisation. Can be downloaded from http://ibug.doc.ic.ac.uk/resources/300-W/. To use the main files associated to this dataset, unzip the dataset into any desired folder, and modify the following line in the corresponding main files to point to this directory:

path = '/home/cvc/moliu/Datasets/300w/'

<b>BU4DFE Synthesised:</b><br/>
A modified version of BU4DFE, with artificial rotations for a wide range of pitch and yaw angles. The dataset is linked to the main scripts in the same way as 300-W. A script 
is also provided to generate the BU4DFE-S dataset from BU4DFE. It is found under the bu4dfes folder.

<b>TODO: Upload this dataset</b>

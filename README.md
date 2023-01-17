This repository contains files in fulfilment of the requirements for the degree of Master of Philosophy. 
ECM_robust contains an Epsilon constraint method for solving a robust flow shop model. The data is randomly generated. It was written in the Julia programming language. 
The data used in the thesis is stored the processing_times_final.txt. This data was randomly generated. The ECM_robust file has capability to generate random data. It also has capability to read in data from a text file. 
The data is stored in a single column. It should be read into a 3x6x1000 array. It is read into the dimensions left to right. Eg: 
[1,1,1]
[2,1,1]
[3,1,1]
[1,2,1]
[2,2,1]
[3,2,1]
[1,3,1]
…
[3,6,1]
[1,1,2]
[2,1,2]
…
[3,6,1000]

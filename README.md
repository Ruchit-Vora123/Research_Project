# Research project- Lakehead University
## Research Methodology (5112-GDF) 
<h1>Implementing Cryptographic Algorithms For Secure Transmission</h1>

## Table of Contents

1. [Documentation](#documentation)
2. [Introduction](#Introduction)
3. [Prerequisites](#Prerequisites)
4. [Aim](#Aim)
5. [Working Mechanism](#Working-Mechanism)
6. [Cryptography Algorithms](#Cryptography-Algorithms)
7. [Implementation of code](#Implementation-of-code)
8. [Future Scope](#Future-scope)
9. [Result](#result)

## Documentation

- Documents that are containing in this repository are being listed below:

- DES.ipynb ----------> contains code for DES algorithm
- AES.ipynb ----------> contains code for AES algorithm
- SHA.ipynb ----------> contains code for ShA algorithm
- Blowfish.ipynb ----------> contains code for Blowfish algorithm
- RSA.ipynb ---------> contains codev for RSA algorithm using python library
- RSA_Scratch.ipynb ---> contains code for RSA algorithm from scratch
- Images --------> Contains the iamges for the readme file
- README.md ----> This markdown file you are reading.






## Introduction
Cryptography
plays an important role to provide security to
the network. Cryptography can be defined as
technique associated to convert plain text into
intelligible text (human unreadable format) and
vice-versa. Because of this only user who is
intended to receive the information can read. Cryptography is not only used to protect our
data but also used for user authentication.
## Prerequisites
- Google colab - Tensorflow version #if not working use 1.14 version of tensforflow for palceholder
- Numpy
- Sklearn
- scipy
- PyCrypto
- time
- math


## Aim
To acheive security in transmission network, various cryptography algorithm have been proposed. I have implemented some of them in python programming language.
Main aim of this project is to find which is the best suitable algorithm according to evaluation criteria(Encryption time and Avalanche Effect).



## Cryptography Algorithm
- DES, AES, Blowfish ---> These algorithms are symmetric key algorithms(secret key cryptography)
- RSA,SHA ----> These algorithms are Asymmetric key cryptography(Public key cryptography)


## Implementation of code

- <h3>Importing libraries</h3>
    
    ![libraries](images/libraries.PNG)

- <h3>Setting parameter</h3>

    ![settingparameters](images/settingparameters.PNG)

- <h3>preparing dataset</h3>

    ![datasetimport](images/datasetimport.PNG)

- <h3>Function implementation</h3>

    ![modelpreparing](images/modelpreparing.PNG)

- <h3>Train Network</h3>

    ![trainandtest](images/trainandtest.PNG)

## Result

- This project is done very accurate with the satisfied accuracy obtained after the testing result that is about 96,77\% of testing accuracy and 97.5\% of training accuracy for the precision of the analysis for the six different position for 2D stance detection of human activities.

![confusionmatrix](images/confusionmat.PNG)

![graph](images/graph.PNG)


## Future Scope

- Based on a baseline of normal motion, additional study will be done into the usage of more nuanced activity classes, such as walking versus running, agitated movement against calm movement, and perhaps normal versus aberrant behaviour. 
-  A validation of dataset and will try new dataset in this model
- A pipeline for qualitative results 
- Adding Dropout
- Comparison of effect of changing batch size






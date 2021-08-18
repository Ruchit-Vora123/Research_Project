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
- Google colab 
- Tensorflow version #if not working use 1.14 version of tensforflow for palceholder
- Numpy
- Sklearn
- scipy (to calculate hamming distance)
- PyCrypto(contains library for cryptography algorithms)
- time (to calculate encryption time)
- math 


## Aim
To acheive security in transmission network, various cryptography algorithm have been proposed. I have implemented some of them in python programming language.
Main aim of this project is to find which is the best suitable algorithm according to evaluation criteria(Encryption time and Avalanche Effect).



## Cryptography Algorithm
- DES, AES, Blowfish ---> These algorithms are symmetric key algorithms(secret key cryptography)
- RSA,SHA ----> These algorithms are Asymmetric key cryptography(Public key cryptography)


## Implementation of code

- <h3>Importing libraries</h3>
    
    ![libraries](https://github.com/Ruchit-Vora123/Research_Project/blob/main/library.PNG)

- <h3>Encryption</h3>

    ![Encryption](https://github.com/Ruchit-Vora123/Research_Project/blob/main/encryption.PNG)

- <h3>Decryption</h3>

    ![datasetimport](https://github.com/Ruchit-Vora123/Research_Project/blob/main/decryption.PNG)

- <h3>Padding Function</h3>

    ![Padding Function](https://github.com/Ruchit-Vora123/Research_Project/blob/main/padding.PNG)

- <h3>Output</h3>

    ![Output](https://github.com/Ruchit-Vora123/Research_Project/blob/main/output.PNG)
    
    
## Result

- Ouput figures shows that SHA384, RSA, and DES takes large amount of time compare to other algorithms and Blowfish, SHA1, AES takes less amount of time for encryption. Blowfish and SHA1 takes less amount of time so that is efficient in software, at least on some software platforms. And DES has highest avalanche effect among symmetric key algorithms and blowfish has least avalanche effect.

    ![Evaluation Criteria1](https://github.com/Ruchit-Vora123/Research_Project/blob/main/result_encrpytiontime.PNG)

    ![Evaluation Criteria2](https://github.com/Ruchit-Vora123/Research_Project/blob/main/result_hamming.PNG)



## Future Scope

- Evaluate based on some more criteria such as key size, Memory used, Entropy and Number of bits required for encryption optimally
- Implementation of  hybrid algorithms by combining 2 or more cryptography algorithms
- To make one Android App or Website with better user interface




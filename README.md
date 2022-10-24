# Unsupervised spoken term discovery using Diagonal First Search 

## Overview

In this approach, we discover the spoken term similarity in the speech corpus in an unsupervised way in the absolute absence of any linguistic clue. Python-based implementation was demonstrated here. The implementation consists of 

1. Acoustic feature representation 
2. Similarity matching task 

## 1. Acoustic feature representation
In our approach, the acoustic feature representation was obtained from the RASTA-PLP spectrogram. The RASTA-PLP spectral representation was obtained based on https://labrosa.ee.columbia.edu/matlab/rastamat/

## 2. Similarity matching task 

The similarity matching was performed by capturing the similarity at the diagonal level with the depth threshold to obtain similar spoken terms. 


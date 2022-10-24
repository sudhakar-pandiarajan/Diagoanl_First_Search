# Unsupervised spoken term discovery using Diagonal First Search 

## Overview

In this approach, we discover the spoken term similarity in the speech corpus in an unsupervised way in the absolute absence of any linguistic clue. Python-based implementation was demonstrated here. The implementation consists of 

1. Acoustic feature representation 
2. Similarity matching task 

## 1. Acoustic feature representation
In our approach, the acoustic feature representation was obtained from the RASTA-PLP spectrogram. The RASTA-PLP spectral representation was obtained based on https://labrosa.ee.columbia.edu/matlab/rastamat/

## 2. Similarity matching task 

The similarity matching was performed by capturing the similarity at the diagonal level with the depth threshold to obtain similar spoken terms. 

Kindly refer to the python implementation in the repository /demo.ipynb

# Citation 

please cite our work:
```
@article{DFS202202,
title = {Unsupervised spoken term discovery using diagonal first search},
publication = {To be updated},
year = {2022},
doi = {},
url = {},
author = {Sudhakar P and Kishore Kumar R and Sreenivasa Rao K and Pabitra Mitra}
}

```

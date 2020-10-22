This repository contains the JEST 2020/1 IT Initiation Project, parts 1 (under development) and part 2.

# Basic info
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/tamagusko) [![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](LICENSE)  [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)   
© Tiago Tamagusko (tamagusko@gmail.com)  
Version: [CHANGELOG.md](/CHANGELOG.md)  
Project Page: <a href="https://github.com/tamagusko/jest20201">https://github.com/tamagusko/jest20201</a>  

# Environment

Use Python `3.7 or higher`.

Install the required packages with `pip install -r requirements.txt`

# Projects
    
    ├── 1) Predict Pulsar star [2-5] # Classify stars between Pulsar and non-Pulsar (under development)  
    ├── 2) Leukemia Detect [1, 4, 5]  # Classify patients between leukemia or not (under development)  

## Project 1 [[2](#2), [3](#3), [4](#4), [5](#5)] overview:
This is a classification problem. You need to classify a star dataset in Pulsar and non-Pulsar. So, the sample data has a total of 17,898 entries (rows) and 8 features (columns).  

Note: The dataset is unbalanced (non-Pulsar: 16259; Pulsar: 1639).
## Project 2 [[1](#1), [4](#4), [5](#5)] overview:
This is also a classification problem. You need to classify a patient dataset in with leukemia (1) or not (0). Therefore, the sample data has a total of 178  entries (rows) and 186 features (columns).  

Note 1: Only the first 128 entries are labeled, I will use this slice for train and test. The left 50 unlabeled will be used to predict.  
Note 2: Again, the dataset is unbalanced (0: 111 patients; 1: 17 patients).  
Note 3: Feature selection techniques were applied.

# Links
    
> [Project 1: Predict Pulsar](/predictPulsar.ipynb)  
> [Project 2: Leukemia Detect](/leukemiaDetect.ipynb)

# Citation
Tamagusko, T. (2020). Initiation Project JEST 2020/1. Retrieved from https://github.com/tamagusko/jest20201

```bibtex
@misc{TamaguskoJest20201,
  author = {Tamagusko, Tiago},
  title = {Initiation Project JEST 2020/1},
  year = {2020},
  url = {https://github.com/tamagusko/jest20201}
}
```

# References

<a id="1">[1]</a> 
Dataset to support the study. (2020, May 31). 
Retrieved from https://github.com/spingegod/ProjetoTI_part2 

<a id="2">[2]</a> 
Dataset to support the study. (2020, Jun 03). 
Retrieved from https://github.com/spingegod/ProjetoTI_part1 

<a id="3">[3]</a> 
Raj, P. (2020). 
Predicting a Pulsar Star (2020, Jun 03). 
Retrieved from https://www.kaggle.com/pavanraj159/predicting-a-pulsar-star 

<a id="4">[4]</a> 
van Rossum, G. (1995). 
Python tutorial, May 1995. 
WI Report CS-R9526, CS-R9526, 1–65. 

<a id="5">[5]</a> 
Breiman, L. (2001). 
Random forests. 28. 
https://doi.org/http://dx.doi.org/10.1023/A:1010933404324 

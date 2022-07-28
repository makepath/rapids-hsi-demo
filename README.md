# Segmenting roads using hyperspectral imagery and RAPIDs toolkit
---
Requirements:
- RAPIDs toolkit
- NVIDIA GPU

Two options to setup RAPIDs:
1. [Follow instructions for setting up RAPIDS](https://rapids.ai/cloud#GC-single)
2. [(Not tested) New repo for setting up RAPIDs environment](https://github.com/rapidsai/rapids-env-generator)

Download Washington DC mall data:
```
wget -O <path/hsi.zip> http://cobweb.ecn.purdue.edu/~biehl/Hyperspectral_Project.zip
```
Run the `RAPIDS_HSI_Demo.ipynb` notebook

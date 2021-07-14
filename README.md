### Experiment and Environment Meta Info
#### DP-NLP - Analyzing Carbon Footprint of DP-BERT at different degrees of differential privacy; Modelled for Topic Classification
##### Data: [AG News Classification](https://www.kaggle.com/amananandrai/ag-news-classification-dataset?select=train.csv)
System Config: 
PyTorch version: 1.7.0+cu92
CUDA used to build PyTorch: 9.2
ROCM used to build PyTorch: N/A

OS: Ubuntu 18.04.5 LTS (x86_64)
GCC version: (Ubuntu 7.5.0-3ubuntu1~18.04) 7.5.0
Clang version: 6.0.0-1ubuntu2 (tags/RELEASE_600/final)
CMake version: version 3.12.0
Libc version: glibc-2.26

Python version: 3.7 (64-bit runtime)
Python platform: Linux-5.4.109+-x86_64-with-Ubuntu-18.04-bionic
Is CUDA available: True
CUDA runtime version: 11.0.221
GPU models and configuration: GPU 0: Tesla T4
Nvidia driver version: 460.32.03

#### Scripts 
```
1. DPLSTM_v2.ipynb: : DPLSTM for News Classification
2. BERTNewsClassificationDP.ipynb: : Privacy Variant Experiments with BERT
3. BERTNewsClassification.ipynb: : Non-Privacy Variant Experiments with BERT ( ~ epsilon = infinity ) 
4. Visualization.ipynb: Visualizer 
```

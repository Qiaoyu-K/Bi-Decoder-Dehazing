Single image dehazing using a novel bi-stream network
by Qiaoyu Ma, Shijie Wang et al.    
Artificial Intelligence and Computer Vision Laboratory, College of Electronics and Information, Qingdao University

### Dependencies and Installation

* python3
* PyTorch 1.8
* NVIDIA GPU+CUDA
* numpy
* matplotlib


### Datasets Preparation

Dataset website:[RESIDE](https://sites.google.com/view/reside-dehaze-datasets/) ; 
Paper arXiv version:[[RESIDE: A Benchmark for Single Image Dehazing]
(https://www.google.com/url?q=https%3A%2F%2Farxiv.org%2Fpdf%2F1712.04143.pdf&sa=D&sntz=1&usg=AFQjCNHzdt3kMDsvuJ7Ef6R4ev59OFeRYA)]

<details>
<summary> FILE STRUCTURE </summary>

```
    Bi-Decoder master
    |-- README.md
    |-- net
	-- models
	-- data_utils.py
  	-- main.py
 	-- metrics.py
	-- option.py


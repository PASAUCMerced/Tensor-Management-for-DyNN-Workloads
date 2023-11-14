---

# Enabling Large Dynamic Neural Network Training with Learning-based Memory Management

## Introduction
The project uses a learning-based method to enable tensor offloading for Dynamic Neural Networks (DyNN) training. Due to the dynamics of DyNNs, the repeatability of neural network training no longer exists. We propose a novel learning-based method to address the dynamism in DyNNs. Specifically, we leverage program idioms defined in terms of memory access patterns to encode the model architecture of various DyNNs. Furthermore, we use a neural network, termed the pilot model, to increase the predictability of tensor accesses in DyNNs, thereby facilitating memory management.



## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Publication](#publication)

## Installation
Steps to install the project.

```bash
# Example command to install the project
git clone https://github.com/your-username/your-repository.git
```

## Usage
How to use the project after installation.

## Code Structure
Below is an overview of the main folders and their hierarchy in this project:

```
project-title/
│
├── idioms_based_representation_for_op/
│   ├── idiom_generating_tool
│   ├── idiom-based_representation.pdf
│   └── README.md
│
├── pilot_model/
│   ├── model.py
│   ├── train.py
│   ├── inference.py
│   └── README.md
│
│── runtime_mm/
│   ├── tensor_fetch.patch
│   └── README.md
│
└── DyNNs
```

### Folder Descriptions
1. **idioms_based_representation_for_op**
   - **Description**: The idiom_based 
   - **Contents**: Key files or subfolders.

2. **Folder_2_Name**
   - **Description**: Brief description of what this folder contains and its purpose.
   - **Contents**: Key files or subfolders.

3. **Folder_3_Name**
   - **Description**: Brief description of what this folder contains and its purpose.
   - **Contents**: Key files or subfolders.

## Publication
```
@article {dynn-offload24,
	author = {Jie Ren, Dong Xu, Shuangyan Yang, Jiacheng Zhao, Zhicheng Li, Christian Navasca, Chenxi Wang, Harry Xu, and Dong Li. },
	title = {Enabling Large Dynamic Neural Network Training with Learning-based Memory Managemen},
	year = {2024},
	publisher = {In 30th International Symposium on High-Performance Computer Architecture.}
```


# Tensor-Management-for-DyNN-Workloads

Idiom-based representation in operators is in [PDF](idiom-based_representation.pdf)


Absolutely, I can adjust the README template accordingly. Here's a revised version without the "Contributing" and "License" sections, and with an added "Citations" section for referencing external sources or acknowledging contributions:

# Guarateed Non Local Cumulene Dataset


## Overview

This dataset is designed as a comprehensive challenge for machine learning force fields. It focuses on the task of regressing energy and forces from 3D molecular structures. The dataset consists of cumulenes, which due to their electronic structure, exhibit non-local effects. These pose a challenge for conventional machine learning force fields, including both attention-based and message-passing neural networks.

The dataset was published along with the Matrix Function Network paper:

> **Equivariant Matrix Function Neural Networks**
> I Batatia, LL Schaaf, H Chen, G Csányi, C Ortner, FA Faber
International Conference on Learning Representations (ICLR) 2024

 which introduces a novel architecture designed to capture non-local effects. Please see the original manuscript for more details on the dataset and architecture. 

## Usage
The data is stored in extended `xyz` file format as a simple text file, containting the positions, chemical elements, forces and energies. It is usefull to read these using the `Atomic Simulation Envionrment` package which is pip installable. 

## Citing

When using the dataset please cite the original paper. 
```
@inproceedings{batatia2023equivariant,
  title={Equivariant Matrix Function Neural Networks},
  author={Batatia, Ilyes and Schaaf, Lars L and Chen, Huajie and Cs{\'a}nyi, G{\'a}bor and Ortner, Christoph and Faber, Felix A},
  booktitle={International Conference on Learning Representations (ICLR) 2024},
  year={2023}
}
```
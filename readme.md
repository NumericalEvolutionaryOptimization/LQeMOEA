# An Evolutionary Approach for the Computation of $\epsilon$-Locally Optimal Solutions for Multi-Objective Multimodal Optimization

This repository contains the algorithmic resources for the paper:

***An Evolutionary Approach for the Computation of ϵ-Locally Optimal Solutions for Multi-Objective Multimodal Optimization***

## Repository Structure

The repository is organized into four main ZIP archives, each containing the implementation of one of the algorithms introduced and analyzed in the paper.

```
├── Algorithm 1 - ArchiveUpdateLQeps.zip
├── Algorithm 2 - ArchiveUpdateLQepsB.zip
├── Algorithm 3 - LQepsMOEA.zip
└── Algorithm 4 - LQepsMOEA-PT.zip
```

## Algorithms Overview

Below is a high-level description of each algorithm. For full details, please refer to the paper.

### **Algorithm 1 - ArchiveUpdateLQeps**

Archiver that aims to capture the set $L_{Q,\epsilon}$. See also 
```
@ARTICLE{LQeps-I,
  author={Rodriguez-Fernandez, Angel E. and Schäpermeier, Lennart and Hernández, Carlos and Kerschke, Pascal and Trautmann, Heike and Schütze, Oliver},
  journal={IEEE Transactions on Evolutionary Computation}, 
  title={Finding $\epsilon$-Locally Optimal Solutions for Multi-Objective Multimodal Optimization}, 
  year={2024},
  doi={10.1109/TEVC.2024.3458855}
}
```

### **Algorithm 2 - ArchiveUpdateLQepsB**

Bounded version of ArchiveUpdateLQeps.

### **Algorithm 3 - LQepsMOEA**

This evolutionary algorithm directly uses ArchiveUpdateLQepsB for the selection process and hence does not need an external archive for the computation of $\epsilon$-locally optimal solutions.

### **Algorithm 4 - LQepsMOEA-PT**

A hybrid of LQepsMOEA with a multi-objective continuation method, in case the gradient information is at hand.

## Citation

If you use any of these algorithms or this repository in your research, please cite the associated paper:

```
@ARTICLE{LQeps-II,
  author={Hernández, Carlos and Rodriguez-Fernandez, Angel E. and Schäpermeier, Lennart and Cuate, Oliver and Trautmann, Heike and Schütze, Oliver},
  journal={IEEE Transactions on Evolutionary Computation}, 
  title={Finding $\epsilon$-Locally Optimal Solutions for Multi-Objective Multimodal Optimization}, 
}
```

## Contact

For questions or issues, please contact the authors.

# ARLOFF: Autonomous Recursive Local Outlier Factor

This repository provides the implementation of **Autonomous Recursive Local Outlier Factor (ARLOFF)**, a fully parameter-free outlier detection algorithm.

ARLOFF is designed to operate without any user-defined parameters. Instead of using a fixed number of nearest neighbors, the algorithm adaptively determines neighborhood size based on empirical mutual distance characteristics within the data. As a result, the number of neighbors varies dynamically across different regions of the dataset, enabling density-aware anomaly detection.

The algorithm incorporates a **recursive updating mechanism**, making it computationally and memory efficient. ARLOFF updates required statistics incrementally and does not need to store or reprocess all historical data points, which makes it suitable for efficient large-scale processing.

---

## Main Implementation

The core implementation is provided in:
`ARLOFF.ipynb`

The notebook includes:
- Complete ARLOFF algorithm implementation  
- Step-by-step computational procedure  
- Experimental evaluation setup  

---

## Dataset

This repository includes the **Pima dataset** for demonstration and evaluation.

The dataset is publicly available from:

S. Rayana, *ODDS Library*, 2016  
http://odds.cs.stonybrook.edu/

---

## Key Features

- Fully autonomous (no parameter tuning required)  
- Adaptive neighborhood selection  
- Density-aware local outlier detection  
- Recursive update mechanism  
- Computationally efficient  
- Memory efficient
- Build for offline environment

---

## Usage

1. Clone this repository.
2. Open `ARLOFF.ipynb`.
3. Run all cells to reproduce the implementation and experiments.
4. Replace the dataset section to evaluate ARLOFF on other datasets if desired.

---

## Citation

If you use ARLOFF in your research, please cite:

```bibtex
@INPROCEEDINGS{11213522,
  author={Basheer, Muhammad Yunus Iqbal and Mohd Ali, Azliza and Nordin, Sharifalillah and Hamimah Abdul Hamid, Nurzeatul},
  booktitle={2025 6th International Conference on Artificial Intelligence and Data Sciences (AiDAS)}, 
  title={Autonomous Recursive Local Outlier Factor (ARLOFF)}, 
  year={2025},
  pages={301-305},
  doi={10.1109/AiDAS67696.2025.11213522}
}

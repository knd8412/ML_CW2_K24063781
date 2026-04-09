# ML Coursework 2 — Kamyar Nadarkhanidinehkaboudi K24063781

Reproducing the **TypiClust (TPC_RP)** algorithm from Hacohen et al. (2022) on CIFAR-10, and proposing a PCA-enhanced modification.

## Files

- `tpc_rp_cifar10.ipynb` — Task 1: original TPC_RP implementation (SimCLR training, clustering, typicality-based selection, evaluation)
- `task3_pca_modified.ipynb` — Task 3: PCA-enhanced version of TPC_RP
- `*.png` — plots used in the report

## Running

Both notebooks were developed and tested on Google Colab with a T4 GPU. Dependencies (torch, torchvision, scikit-learn, etc.) are listed in the first cell of each notebook.

=== sub-challenge 1 ===

train_cli.tsv: this file contains clinical information (gender and msi status) for the 80 training samples (53 females, 27 males & 18 MSI-High, 62 MSI-Low/MSS).
train_pro.tsv: proteomics data based on spectral counting. Each row represents a protein and each column represents
               a training sample.
sum_tab_1.csv: mislabeling information for the training samples. 1: clinical and 
               proteomics data not from the same sample (mismatch, n=12), 0: both data from the same sample (match, n=68).
test_cli.tsv:  this file contains clinical information (gender and msi status) for the 80 testing samples (31 females, 49 males & 14 MSI-High, 66 MSI-Low/MSS). 
test_pro.tsv:  similar to train_pro.txt, but for testing samples.

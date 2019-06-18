# Lymph_node_metastasis_detection
Identify metastatic tissue in histopathologic scans of lymph node sections

Datasets obtained from kaggle competition https://www.kaggle.com/c/histopathologic-cancer-detection/data

# Project Aim:
### Create an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans
Binary classification of H&E pathology images of lymph node sections into 2 classes:
  * 0: `neg` -- The center 32x32px region of a patch doesn't contain a single tumor cell
  * 1: `pos` -- The center 32x32px region of a patch contains at least one pixel of tumor tissue


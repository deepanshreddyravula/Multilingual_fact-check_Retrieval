# MultiClaim Dataset Directory

This directory is configured to store the MultiClaim dataset files required by the notebook pipeline.

## Required Dataset Files

1. `fact_check_post_mapping.csv` (~2.7 MB) - Included in the repository.
2. `fact_checks.csv` (~493 MB) - **Excluded from Git** due to GitHub's 100 MB file size limit.
3. `posts.csv` (~185 MB) - **Excluded from Git** due to GitHub's 100 MB file size limit.

---

## Dataset Acquisition

The dataset originates from the **MultiClaim** benchmark published on Zenodo:
- **Zenodo Record:** [MultiClaim: A Benchmark for Multilingual Fact-Checking](https://zenodo.org/records/7737983)
- **Persistent Identifier (DOI):** `10.5281/zenodo.7737983`

### Instructions to Download

1. Visit Zenodo: [https://zenodo.org/records/7737983](https://zenodo.org/records/7737983)
2. Download the compressed dataset archive (`dataset_4.zip` or the individual CSV files).
3. Extract `posts.csv` and `fact_checks.csv` into this `dataset/` directory:
   ```bash
   # Expected layout:
   dataset/
   ├── fact_check_post_mapping.csv
   ├── fact_checks.csv
   ├── posts.csv
   └── README.md
   ```
4. If running on **Google Colab**, upload the files to your Google Drive under:
   `My Drive/MultiClaim/dataset/` (or place `dataset_4.zip` in `My Drive/MultiClaim/`). The notebook will automatically detect and mount it.

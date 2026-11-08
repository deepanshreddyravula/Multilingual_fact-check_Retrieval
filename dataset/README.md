# MultiClaim Dataset Directory

This directory is configured to store the MultiClaim dataset files required by the notebook pipeline.

## Required Dataset Files

1. `fact_check_post_mapping.csv` (~2.7 MB) - Included in the repository.
2. `fact_checks.csv` (~493 MB) - **Excluded from Git** due to GitHub's 100 MB file size limit.
3. `posts.csv` (~185 MB) - **Excluded from Git** due to GitHub's 100 MB file size limit.

---

## Dataset Acquisition

The dataset is available directly from this repository's **v1.0.0 GitHub Release** as well as the original Zenodo benchmark:

### 1. Direct Download from GitHub Release (Recommended)
You can download the full compressed dataset archive (`dataset.zip`, 138 MB) directly from the repository release:
- **Direct Download Link:** [https://github.com/deepanshreddyravula/Multilingual_fact-check_Retrieval/releases/download/v1.0.0/dataset.zip](https://github.com/deepanshreddyravula/Multilingual_fact-check_Retrieval/releases/download/v1.0.0/dataset.zip)

Or via command line:
```bash
curl -L -O https://github.com/deepanshreddyravula/Multilingual_fact-check_Retrieval/releases/download/v1.0.0/dataset.zip
unzip dataset.zip
```

### 2. Original Zenodo Benchmark
- **Zenodo Record:** [MultiClaim: A Benchmark for Multilingual Fact-Checking](https://zenodo.org/records/7737983)
- **Persistent Identifier (DOI):** `10.5281/zenodo.7737983`
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


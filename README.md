# AI Product Intelligence System

This repository contains a Python notebook for building an AI-powered product intelligence workflow for fashion catalog analysis. The project demonstrates:

- text-to-product search using CLIP embeddings
- image-based reverse product search
- BLIP-powered image captioning
- duplicate detection and catalog deduplication
- complementary product recommendation
- embedding visualizations with PCA

## Project Files

- [ai-product-intelligence-system.ipynb](ai-product-intelligence-system.ipynb) — main notebook with the full workflow
- [ai_product_intelligence_report.pdf](ai_product_intelligence_report.pdf) — generated project report (ignored by Git)

## Requirements

Install the required Python dependencies with:

```bash
pip install -r requirements.txt
```

## Setup

1. Create and activate a Python environment.
2. Install the dependencies from the requirements file.
3. Open the notebook and run the cells in order.

> The notebook is written for a Kaggle-style environment and expects the fashion dataset under a Kaggle input path. If you are running it locally, update the `DATASET_ROOT` path in the notebook to point to your local dataset directory.

## Usage

The notebook covers three main product intelligence use cases:

1. Reverse product search from natural-language queries
2. Duplicate product detection and catalog cleanup
3. Complementary product recommendations for styling

## Notes

- A GPU is optional, but it will speed up model inference.
- The generated report PDF is intentionally excluded from version control.

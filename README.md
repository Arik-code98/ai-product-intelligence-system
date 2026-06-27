# AI Product Intelligence System

This repository contains a complete notebook-based workflow for building an AI-powered product intelligence system for fashion catalogs. It combines computer vision and natural language understanding to support product discovery, catalog cleanup, and recommendation tasks.

## What this project does

The notebook demonstrates a practical end-to-end pipeline for:

- reverse product search from natural-language queries using CLIP embeddings
- image-based similarity search for product retrieval
- BLIP-generated image captions for richer product understanding
- duplicate detection and catalog deduplication
- complementary product recommendation for styling and outfit planning
- embedding visualization with PCA for exploratory analysis

## Repository contents

- [ai-product-intelligence-system.ipynb](ai-product-intelligence-system.ipynb) — main notebook containing the full workflow
- [ai_product_intelligence_report.pdf](ai_product_intelligence_report.pdf) — project report generated from the analysis
- [requirements.txt](requirements.txt) — Python dependencies for the notebook
- [.gitignore](.gitignore) — repository ignore rules

## Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt
```

## Setup

1. Create and activate a Python environment.
2. Install the required packages from [requirements.txt](requirements.txt).
3. Open [ai-product-intelligence-system.ipynb](ai-product-intelligence-system.ipynb) and run the cells in order.

> The notebook was originally designed for a Kaggle-style environment and expects the fashion dataset under a Kaggle input path. If you are running it locally, update the dataset paths in the notebook to match your local folder structure.

## Workflow overview

The notebook is organized around three core product intelligence use cases:

1. Text-to-product search
   - Converts search queries into embeddings and retrieves visually similar products.

2. Duplicate detection
   - Identifies near-duplicate products and builds a cleaner catalog.

3. Complementary recommendations
   - Suggests products that fit a style or outfit context based on category, usage, and color compatibility.

## Notes

- A GPU is recommended for faster model inference, but CPU execution is also possible.
- The report PDF is tracked in this repository so it is easy to share and review.
- If you want to reproduce the full results, make sure the dataset files are available before running the notebook.

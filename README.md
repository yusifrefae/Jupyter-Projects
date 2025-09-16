# Jupyter Finance Projects
Jupyter notebooks that use Python to do Finance coding tutorials

A small collection of reproducible Jupyter notebooks for quick finance experiments and tools I use in my trading workflow.  

Practical, compact, and runnable — intended to show the actual analysis and decisions I make (not a polished product).

## Featured notebook
**Pulling Stock Data to Analyze Companies** — quick demo using `yfinance` to fetch company metadata and key KPIs.  
Path: `notebooks/Pulling-Stock-Data-to-Analyze-Companies.ipynb`

(You can run the notebook in Colab — open it and choose **Open in Colab**.)

## Quick summary
- Purpose: pull historical & metadata, create simple features (Trend/Lag), and produce quick, interpretable outputs (used weekly for trade sizing).  
- What to expect: runnable notebooks, small sample data in `/data`, and one-page summaries for easy screening.  
- Who this is for: hiring managers, data/finance teams, and anyone who likes reproducible analysis.

## How to run
1. Open the notebook in GitHub and click **Open in Colab** (recommended), or clone the repo and run locally.  
2. Requirements (if running locally): `pandas`, `yfinance`, `scikit-learn`.  
```bash
pip install pandas yfinance scikit-learn

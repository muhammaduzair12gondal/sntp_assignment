# SNTP Assignment 01 — Political Blogosphere Network Analysis

## Overview
Analysis of the political blogosphere hyperlink network (Adamic & Glance, 2005):
directed graph construction, centrality analysis (PageRank, Betweenness), a
centrality-informed node-removal experiment, Louvain community detection, and
pairwise evaluation against ground-truth political labels.

## Setup

1. Create and activate a virtual environment:
```bash
python -m venv venv

venv\Scripts\activate        # Windows

source venv/bin/activate     # Mac/Linux
```
2. Install dependencies:
```bash
pip install networkx matplotlib pandas numpy scipy python-louvain scikit-learn
```
## Data
Place `polblogs.gml` in the `data/` folder. Source: Adamic, L. A., and Glance, N. (2005),
"The Political Blogosphere and the 2004 U.S. Election," available at
https://public.websites.umich.edu/~mejn/netdata/

## Running
Open `notebooks/analysis.ipynb` in VS Code (or Jupyter) and run all cells top to bottom.
All random seeds are fixed and documented in the Part F section of the notebook for
reproducibility.

## Structure
- `notebooks/analysis.ipynb` — full analysis, Parts A–F
- `data/` — raw and cleaned graph files
- `report/` — IEEE-format PDF report and LaTeX source

## Author
Uzair — Roll No. 23F-3032, SE4095 Social Network Theory and Practice
